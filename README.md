### Hi there!
# Im Nyanggi! I am a Golang developer, living in Korea!
```go
package main

import (
  "fmt"
)

func main() {
  fmt.Println(AboutMe("Nyanggi"))
}  

func AboutMe(Nyanggi string) []string {  
  Nyanggi.language = "Golang"
  Nyanggi.subLanguage = "Typescript"
  Nyanggi.MainTools = "Visual Studio Code"
  Nyanggi.age = "-1"
  Nyanggi.contact = "Discord: 냥이#6162"
  Nyanggi.about_me = "A Normal Student Developer Using Golang"
  return Nyanggi.language, Nyanggi.subLanguage, Nyanggi.MainTools, Nyanggi.age, Nyanggi.contact, Nyanggi.about_me
}
```
