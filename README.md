### Hi, I'm Bingrui Guo 👋

##### Mathematics & Computer Science Student @ University of California - San Diego


```cpp
#include <iostream>
#include <string>
using namespace std;
class BingruiGuo {
  public:
    BingruiGuo(const string &, const string &);
    string Languages(){ return "C++, HTML5/CSS/JS, Python, Java";};
    string tools(){ return "Github, Docker, Unreal Engine";};
    string lifeQuote(){ return "Empty your mind. Be formless, shapeless — like water.";};
  private:
    string firstName;
    string lastName;
};

int main()
{
  BingruiGuo BG("Bingrui", "Guo");
  BG.Languages();
  BG.tools();
  BG.lifeQuote();
  return 0;
}

```


![visitors](https://visitor-badge.glitch.me/badge?page_id=JayBingruiG.JayBingruiG)
