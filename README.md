pseudowords 
===========
*To be uploaded*

***Because sometimes we just need localized strings for testing...***


This project leverages pseudolocalization-tool (https://code.google.com/p/pseudolocalization-tool/) and jlorem (https://github.com/oliverdodd/jlorem) to produce localized (or not) lorem ipsum.  The java API can return words, sentences, paragraphs, or simply localize a user defined string.  



Usage
---
**Example 1**
```Java  
  String message = PseudoWords.getLocalizedWords(50)
```
**Output**
```
ŕîšûš ƒéûĝîåţ ļåçûš ṽîṽéŕŕå þŕåéšéñţ åð ṽîṽåɱûš éĝéţ ļåçîñîå ṽéļîţ ééļýåķ ñåĝöļ ĥåƀîţåñţ ţûŕþîš šöçîîš ðöñéç ɱåĝñå îñ šéɱþéŕ ƒéûĝîåţ îñţéŕðûɱ ñûļļå ñöšţŕå šûšçîþîţ éĝéţ ţûŕþîš îñçéþţöš ĥîɱéñåéöš ļîţöŕå ĥéñðŕéŕîţ îñţéŕðûɱ ɱåššå ĝŕåṽîðå éĝéšţåš ṽéĥîçûļå ñîƀĥ þåŕţûŕîéñţ åŕçû ļîĝûļå ļîĝûļå îñţéĝéŕ îñçéþţöš þûļṽîñåŕ ñåĝöļ ñéǫûé ñîšļ ðîš éĝéšţåš šûšþéñðîššé ļîĝûļå
```

**Example 2**
```Java 
  PseudoWords.getWords(50)
```
**Output**
```
rhoncus vehicula tincidunt in suspendisse posuere euismod donec egestas mus laoreet sem a eu malesuada dapibus scelerisque pulvinar facilisis suspendisse nulla venenatis facilisis vestibulum dignissim nibh augue sed montes a ultricies ligula tincidunt amet nibh quisque magnis sagittis sed orci interdum convallis interdum pulvinar laoreet rhoncus sed dapibus netus hendrerit 
```
**Example 3**
```Java 
  PseudoWords.localize("my string")
```
**Output**
```
 ɱý šţŕîñĝ
```
