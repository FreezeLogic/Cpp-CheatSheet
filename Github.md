# GitHub *.md syntax  
 
## Headings
\# The largest heading <br/>
\#\# The second largest heading <br/>
\#\#\#\#\#\# The smallest heading <br/>

# The largest heading
## The second largest heading
###### The smallest heading
<br/>

## Basic formating  

Style              |	Syntax         | Keyboard shortcut   | Example                                      | Output
------------------ |--------------- | ------------------- | -------------------------------------------- | -------
Bold               | ** ** or __ __ | command/control + b | \*\*This is bold text\*\*                    | **This is bold text** 
Italic             | * * or _ _     | command/control + i | \*This text is italicized\*                  | *This text is italicized*
Strikethrough      | ~~ ~~          |                     | \~\~This was mistaken text\~\~               | ~~This was mistaken text~~ 
Bold and italic    | ** ** and _ _  |                     | \*\*This text is \_extremely\_ important\*\* | **This text is _extremely_ important**
Add more spaces    | \&nbsp\;       |                     |here\&nbsp\;\&nbsp\;\&nbsp\;\&nbsp\;4 space | here&nbsp;&nbsp;&nbsp;&nbsp;4 space
Line break         | two spaces or \<br\/\> tag |         | This is two \<br\/\> line text               | This is two <br/> line text
Fenced code blocks\*| \`\`\` \`\`\`  |                     | \`\`\` var x = 1;\`\`\`                      |  ``` var x = 1;```

\*Code blocks highlighting example <br/>
Code must be placed on the new line after first \`\`\` tag, and after code end close tag \`\`\` must be on new line.<br/>
This code <br/>
\`\`\`Go <br/>
import "fmt" <br/>
func main() { <br/>
&nbsp;&nbsp; fmt.Println("Hello, 世界") <br/>
}
\`\`\` <br/>
now formated as <br/>
```go
import "fmt"
func main() {
    fmt.Println("Hello, 世界")
}
```
List of syntax highlighting support in YAML file https://github.com/github/linguist/blob/master/lib/linguist/languages.yml
