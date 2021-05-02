```C#
using Human;
using World;

public class JourneyCherry : Human
{
      private string m_Hobby = "Game";
      private string m_Language = "Korean";       //TODO : add English, Japanese
      private string m_ProgrammingLanguage = "C"; //It can be changed.
      private string m_Company = null;
      
      public string ToString()
      {
            return "Hello World!";
      }
}

class World
{
      static void Main(string[] args)
      {
            JourneyCherry me = new JourneyCherry();
            Console.WriteLine(me);
      }
}
```
