### Hi there!
# Im Nyanggi! I am a Golang, Unity Developer, living in Korea!
<!--
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```go
package aboutMe
import (
  "fmt"
  "math"
)

func main() {
  fmt.Println(AboutMe("Nyanggi"))
}  

func AboutMe(Nyanggi string) []string {  
  Nyanggi.language = "Golang"
  Nyanggi.subLanguage = "Javscript"
  Nyanggi.MainTools = "Visual Studio Code, Unity"
  Nyanggi.age = math.Inf(1)
  Nyanggi.contact = "Discord: Nyanggi#8389"
  Nyanggi.about_me = "A Normal Student Developer Using Golang"
  return Nyanggi.language, Nyanggi.subLanguage, Nyanggi.MainTools, Nyanggi.age, Nyanggi.contact, Nyanggi.about_me
}
```
