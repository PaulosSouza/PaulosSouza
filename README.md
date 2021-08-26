# Hi there, PH here 👋

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/paulo-henrique-89b148166/)](https://www.linkedin.com/in/paulo-henrique-89b148166/)
[![Mail Me!](https://img.shields.io/badge/-Contact%20Me!-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:arthur.diegoo@hotmail.com)](mailto:phferreirasouza106@gmail.com)

<div style="display: flex; width: 100%; justify-content: center; align-items: center;">
  <img style="margin-right:  50px" src="./assets/rockGif.gif" width="200" height="200"/>
</div>

```cs

public class Human {

  protected string Name { get; set;}
  protected string Nationality { get; set; } 
  protected string Me { get; set; }
  
  public string FavoriteBand { get; set; }
  public List<object> Technologies { get; set; } = new List<object>();
  public List<string> Languages {get; set;} = new List<string>();

  public Human() {

    // About me
    this.Name = "Paulo Henrique";
    this.Nationality = "Brazilian";
    this.FavoriteBand = "Hands Like House";
    this.Me = "Music enthusiastic | Programming lover ❤";

    // Tecnologies
    this.Technologies.Add(new 
    {
        Javascript = new string[]     { "ReactJS", "Appium", "Nodejs" },
        Csharp = new string[]         { "ASP.NET Core", "Universal Windows Platform" },
        APIs = new string[]           { "REST", "OData", "SOAP" },
        CloudComputing = new string[] { "Azure", "Azure Functions", "SOAP" }
    });

    //Languages
    this.Language.Add("Fluent Portuguese");
    this.Language.Add("Intermediate English");
  }
}
```

`💬 Let's talk about C# and Javascript?`