```C#
using Human;
using World;

public class JourneyCherry : Human
{
      private string m_Hobby = "Game";
      private string m_Language = "Korean";       //TODO : add English, Japanese
      private string[] m_ProgrammingLanguages = new string[]{
            "C",
            "C#", //for Unity
            "Java",
            "Erlang"
      };
      private string m_Company = null;
      
      public override string ToString()
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
