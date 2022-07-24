# Guiding Principals

Need an intro here?

1.  Backward compatibility trumps everything  
    twinBASIC was born out of the desire to provide an upgrade path for Visual Basic 6 and VBA. We fully believe that breaking compatibility, even to upgrade something that was working is always risky and nobody should be forced to rewrite software just to gain new features. As a consequence, twinBASIC will always remain fully compatible with VB6, VBA and future versions of twinBASIC. Any new features introduced must respect that.
    
2.  Community is essential  
    Programming language is never just merely a language. A healthy programming language is one with a healthy ecosystem and to achieve this, we aim to make it easy as possible to share and contribute code and engage with other users.
    
3.  Solving problems is the point  
    twinBASIC, like Visual Basic, is oriented toward helping the users focus on the business problem, rather than the implementation details. To that end, twinBASIC will try to provide good defaults and allow the user to work at the high level. However, the user is free to go lower where it is necessary for the solution.
    
4.  The B in Basic stands for Beginners, still  
    We recognize the historical intent of the original BASIC language as an instructional tool for those new to the world of programming and commit to maintaining that important heritage while also acknowledging the need to enhance the language for more modern technologies and concepts. BASIC was originally intended as a tool for Beginners to learn with, and twinBasic must not only remember and maintain that heritage but also build upon it so that future generations of people new to the world of programming find it welcoming. There should be an approachably sloped learning curve from the early beginnings to the more advanced techniques when new concepts and capabilities are added over time.
    
5.  Readable code is better than terse code  
    Because code is usually read more often, and will be read at different points, we want to encourage and promote writing readable code from the start. The ideal readable code is the one where the user achieves the same mental state as the writer had with minimal effort.
    
6.  Transparency rocks  
    Code that says what it does is far preferable to clever hacks or implicit behaviors. twinBASIC will provide tools to help make implicit explicit and make it easy for users to see the actual behavior. Ideally, the users should never be astonished even if the code is originally gnarly.
    
7.  Consistency matters  
    A consistent language is easier to learn and predict. Furthermore, consistent language makes sharing easier. To that end, twinBASIC will strive for maximum consistency in its syntax & features and make it easy for users to follow a coding style. However, readability takes priority over consistency.
    
8.  Fewer ways are better than many ways  
    twinBASIC aims to push forward but in considering new features, we must take care to assess what already exists, whether there is a legitimate need that is not already met, whether it can be best done by tweaking existing features, and once exhausted, assess how new feature will fit in the overall language’s existing syntax and provides a genuine new way that is clear and as intuitive as possible to the users. We want to minimize synonyms and different ways of saying the same thing unless it can be shown that readability and clarity will trump. Having only one way of doing something where possible, we also make the language easier to use, read and understand.
    
9.  Refactoring and testing should be natural  
    twinBASIC exists expressly to support graceful upgrade of long-lived codebases without forcing a rewrite. Requirements may change but the users must be able to answer the questions on the impact and be able to make changes to the codebase without any fear of breaking the codebase or missing details. Testing should be easy and can be applied even to an existing project, which will in turn directly aid refactoring and proving that the software did not change in unexpected ways.
    
10.  Documentation is important  
    In other languages, documentation is usually an afterthought. twinBASIC will make it easy as possible for users to write documentation and share it with other users.
    
11.  Pure and simple: YOUR Code  
    Compiled twinBASIC code will not come with runtime library, a virtual machine, or some framework. It will come as it is to the end users' computer, in most compact form possible. It will not demand complex registration or installation process. XCopy deployment is the pinnacle.
