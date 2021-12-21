Welcom to my programme
---
# Mein Portfolio
---
## Einführung
Wir haben in einer Gruppe ein Hutspiele erstellt und weiter funktione eingbaut haben.

### Ziel
* Für was dient dieser Code überhaupt da und was wichtig Cod ist und ihre bedeutungen.
* Wie der Code aussehen muss um Daten zu verschicken
*  Mit einem Video zeigen wie man es aus führt

# Inhalt 1
Der erste Code ist die erste From. Der zweite Code ist die zweite Form.
```c#
public partial class Form1 : Form
    {
        public int anzCoins;
 private void button5_Click(object sender, EventArgs e)
        {
            
            Form3 Highscores = new Form3(this);
            Highscores.Show();
        }
        
        }
        
    public partial class Form3 : Form
    {
        public Form1 daddy;
        string path = @"test.txt";
       
       public Form3(Form1 daddy)
        {
            InitializeComponent();
            this.daddy = daddy;
            string fileRead = File.ReadAllText(path);
            richTextBox1.Text = fileRead;
        }
        
        
        
         private void button1_Click(object sender, EventArgs e)
        {

           
            string nameHighscore = eingabeHighscore.Text;

            if (nameHighscore == "")
            {
                nameHighscore = "Unbekannt";
            }
           
            string documentText = $"{nameHighscore}: {daddy.anzCoins} Coins\nHinzugefügt am {DateTime.Now}{Environment.NewLine}";
            File.AppendAllText(path, documentText);

            richTextBox1.Text += documentText;
        }
```
    
    
    
# Inhalt 2
    Dieser Code hat eine Wichtige Funktion bei Windows Form-App und zwar ist es nicht mehr so das man ein Programm aht sonderen mehrer Programm hat. Doch will man irgend wie die Daten von eine Form zur anderen Form bringen und für das ist dieser Code da. Um diese zu machen sind bestimmte Cods wichtig der erste ist `c# Form3 Highscores = new Form3(this);` der erlaubt es in die neu Form zu kommen udn zu estellen, auch muss ihre Varable oder was sie auf  die neu Form reintun wollen muss Public sein das jeder zugriff hat auf diese Dateien.  Der nachste wichtig Code ist der `   public Form1 daddy;` erlaubt Daten von Form 1 zuzugrefien. Weiter Code ist `dadyy.this = daddy`
    Diese erlaubt jetzt das jede variablie mit daddy hat jetzt gleich viele wie die Form1. Ein Beipsile Code ist `daddy.anzConis` das erlaubt das dort die genau gleich anzhal von Conis steht wie bei Form1.

# Verifikation, Reflektion +  Verbesserungen
*Ziel 1 ereicht für was der Code gebraucht wird,wird im Inhalt zwei erklärt.
*Ziel 2 ereicht ich konnte im Inhalt eins mit einem Text das Problem schieldern, wieso der Timer ins Hauptprogramm nicht rein kam.
*Ziel 3 erreicht wie es funktionirt wird mit einem Video dargestellt

*1 Ich konnte  in der Gruppe nicht viele helfen.
*2 ich habe mich nicht gut auf den das codieren Konzentriren können , da immer mehre Idee kamen und so nicht auf meine Code konzentrien kann. 
 
*1  Beim nächsten mal muss ich mehr über Google suchen und auch feagen was mein Teammitglied braucht das er weiter machen kann und das er mir erklärt,wenn erweis waser macht , dass er mir es erklärt und ich so auf andere Idee kommen, um zu helfen.
*2 ich soll in nächsten Projekt, wenn man Teammitglied codiert und ich im helfen sollen. Einen kurzes programm schreiben das ich selber draus komme, was seine Idee ist und wenn weiter Idee kommen die einfügen kann und so auch ich meine Idee sagen kann und euînfügen und auch so auf Lösungen für meine Teammitglieder Probleme.
Gleichzeitg sollte ich mir selber Idee von meinen Teammitglieder aufschreiben und zuhause gedanken machen wie ich Ihnen helfen kann oder ich es Umsetzen würde , wenn ich mich in der Schule auf meinen Code knzentriren kann. SO kann ich immer vorstunden anfang sagen wie ich das gelöst habe oder im zeigen nach was mein Teammitglied suchen muss.
