Dagbok Alexander Malmqvist

## Mån 12/5
Gruppen träffades och vi skrev ett gruppkontrakt. Därefter diskuterade vi några idéer och kom överens om att alla ska fundera vidare till imorgon, så röstar vi och bestämmer vilken idé vi går vidare med då. Vi satte också upp trello och en discord server.

## Tis 13/5
Vi hade ett möte där vi presenterade våra idéer och röstade fram att vi ska utveckla en app med GPS-karta. Appen ska fungera som en skräckinspirerad quizpromenad, där användaren rör sig fysiskt till olika platser markerade på kartan. På varje plats får man svara på en skräckrelaterad fråga – vid rätt svar belönas man med en skatt, medan ett fel svar leder till något läskigt som aktiveras i appen. Vi skrev user stories till appen.

## Ons 14/5
Jag startade ett Xcode-projekt med en .gitignore-fil och pushade upp det till GitHub. Övriga gruppmedlemmar klonade ner projektet, och tillsammans säkerställde vi att alla kunde pusha till repot utan problem. Därefter började vi planera innehållet för sprint 1 och diskutera vilka funktioner som ska prioriteras.

## Tor 15/5
Vi påbörjar sprintplaneringen inför Sprint 1 genom att välja ut de user stories vi vill hinna med under sprinten. Därefter estimerar vi varje story med poäng, och bryter sedan ner dem i mindre konkreta tasks. Möte med bill därefter och vi ligger i fas.

## Mån 19/5
Under dagens möte fördelade vi uppgifter. Jag kommer att börja arbeta med kartfunktionen, jag skapade en LocationManager för att hämta användarens position och en view för att visa kartan tillsammans med den aktuella positionen.

## Tis 20/5
På morgonmötet omformulerade vi vissa user stories och tasks för att bättre spegla det faktiska arbetet efter att vi kommit igång. Jag fortsätter idag med kartfunktionen och implementerar logiken för att slumpa ut kistor. Baserat på användarens aktuella position genereras nu 10 kistor inom en radie på cirka 2 km.

## Ons 21/05
Vi har kommit långt i sprinten och fokuserar nu på att sammanfoga alla delar. Samtidigt för vi diskussioner om hur vi ska ta arbetet vidare framåt. Just nu arbetar jag med att implementera navigeringen från startskärmen till GameView och säkerställa att den fungerar korrekt med kartan och utplacering av kistor.
