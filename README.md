# joaf123@GitHub
```cpp
#include <iostream>
#include <array>

struct Dev{const char*Name,*Title;std::array<const char*,7>Skills;

std::string bio(){std::string r=Name+std::string(" | ")+Title+" | ";for(auto&i:Skills)r+=i+std::string(" ");return r;}};

int main(){
    Dev me{.Name="Joachim Fosse",.Title="Full-Stack Dev",.Skills={".NET",".NET Core","C#","VB.NET","SQL","JS","Pentesting"}};
    std::cout<<me.bio();
}
```

- 🔭 I’m currently working on a full C2C Framework utilizing discord servers as the command server among other small projects :)
- 🌱 I’m currently learning Blazor

<!--
**joaf123/joaf123** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
