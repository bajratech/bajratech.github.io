---
layout : post
number: 9
bajra_weekly: false
comments : true
title : Write your own Code Snippet for VS
tags : Snippet Visual-Studio
author: Chandan Gupta Bhagat
nickname: chandan
---

Write your own Code Snippet for VS
=
Have you ever written bulky codes repeatedly that makes you feel lazy? Have you ever used snippets for fast coding? 

Of course it would be a big **YES!!**. We often write **for** and the press **tab** twice to get following code 

    for (int i = 0; i < length; i++)
    {
     
    }
Again we use **if** and press **tab** twice to get code as below

    if (true)
    {
    
    }

Now its time to write our own code snippets. Just follow the instructions given below.

 1. Create a new file called *.snippet
 2. Paste this code

        <?xml version="1.0" encoding="utf-8"?> 
        <CodeSnippets  
        xmlns="http://schemas.microsoft.com/VisualStudio/2005/CodeSnippet">  
        <CodeSnippet Format="1.0.0">  
            <Header>  
                <Title></Title>  
    			<Shortcut></Shortcut>
    			<Description></Description>
	            <Author></Author>
            </Header>  
            <Snippet>  
                <Code Language="csharp">  
                    <![CDATA[ "code here" ]]>  
                </Code>  
            </Snippet>  
        </CodeSnippet>  
    </CodeSnippets>   

	Things might get messy here so carefully put the values inside the tags.
	As mentioned in the header, we have **Title**, **Shortcut**, **Description** and **Author**. 
	**Title** : Title of snippet
	**Shortcut**: Your shortcut to snippet to double **tap** on it. 
	**Description** : Description of your snippet. You can keep this blank.
	**Author**: Since you are the creator, of course your name here.
	Now the main thing comes in **Code** tag. You can see ![CDATA[ "code here"]]. Write down your code replacing **"code here"**. It doesn't  matter if it is multi-line, just go through it. Don't leave inverted comma " hanging around there. 

 3. Save it.

 4. Now open Visual Studio and goto **Code Snippets Manager** in **Tools
    menu**.
 5. Now goto import and select your code snippet.
 6. After importing, you are ready to go
 7. Type your **shortcut** and double **tab** on it
 
Cheers 
Happy coding 

   
