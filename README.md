https://beam.apache.org/get-started/quickstart-java/

mvn archetype:generate `
  -D archetypeGroupId=org.apache.beam `
  -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples `
  -D archetypeVersion=2.42.0 `
  -D groupId=org.example `
  -D artifactId=word-count-beam `
  -D version="0.1" `
  -D package=org.apache.beam.examples `
  -D interactiveMode=false
   
cd .\word-count-beam

dir .\src\main\java\org\apache\beam\examples

In the word-count-beam directory, create a file called sample.txt. Add some text to the file. For this example

mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner

ls counts*
   
more counts*

Output :

Aside: 1
tell: 1
again: 2
When: 3
bestow: 2
sent: 1
should: 3
gentlemen: 1
calumny: 1
sugar: 1
patient: 1
say: 2
word: 1
death: 2
How: 3
part: 1
Prince: 1
From: 1
majesties: 1
Grating: 1
am: 2
poor: 1
fly: 1
Your: 2
sea: 1
unkind: 1
contumely: 1
as: 10
bodkin: 1
inclined: 1
at: 1
The: 15
fool: 2
honest: 3
lunacy: 1
I: 32
beauty: 4
mind: 3
she: 1
t: 3
do: 9
thank: 1
inoculate: 1
thus: 3
quiet: 1
hope: 1
lisp: 1
blame: 1
need: 1
ecstasy: 1
circumstance: 1
sometime: 1
lawful: 1
Good: 2
remembrances: 1
honesty: 4
order: 1
neglected: 2
harlot: 1
ROSENCRANTZ: 7
for: 10
offences: 1
live: 1
Exeunt: 3
matter: 2
deed: 1
in: 15
snow: 1
if: 3
shall: 11
regard: 1
dream: 1
men: 1
could: 1
question: 2
heart: 3
determination: 1
unmatch: 1
dreams: 1
thousand: 1
No: 3
edge: 1
night: 1
too: 5
against: 1
breath: 1
reason: 1
receive: 2
Must: 1
seas: 1
them: 7
coming: 1
takes: 1
melancholy: 1
free: 1
hither: 1
fashion: 2
But: 5
though: 1
marry: 3
fellows: 1
ambitious: 1
something: 3
seem: 1
ice: 1
Tragedy: 1
Nymph: 1
bells: 1
speech: 1
art: 1
To: 16
cowards: 1
discourse: 1
life: 2
escape: 1
accident: 1
glass: 1
quickly: 1
honey: 1
please: 3
wonted: 1
opposing: 1
house: 1
blown: 1
natural: 1
flesh: 1
speed: 1
doors: 1
exercise: 1
Most: 2
pure: 1
wrong: 1
coil: 1
him: 21
vows: 1
outrageous: 1
