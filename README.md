### Hi there 👋

## Projects
### [wordPractice Discord Bot](https://top.gg/bot/743183681182498906)
- A typing test discord bot centered around improving touch typing skills. 

### [Thomas Coin](https://github.com/principle105/thomas-coin)
- Official Python implementation of the Thomas Coin protocol.


```py

class Programmer(Person):
    def __init__(self, languages: list, colours: list = None):

        self.languages = languages  # Languages known

        if colours is None:
            colours = "No favourite colour :("

        self.colours = colours  # Favourite colours

    def get_hash(self):
        data = self.get_json_data()
        block_string = json.dumps(data, sort_keys=True).encode()
        return sha256(block_string).hexdigest()

    def get_json_data(self):
        data = {
            "languages": self.languages,
            "colours": self.colours,
        }
        return data


me = Programmer(
    languages=["Python", "Javascript", "HTML", "CSS"],
    colours=["Orange", "Purple", "Blue"],
)
```


<details>
  <summary><b>Github Stats</b></summary>

![Github Stats](https://github-readme-stats.vercel.app/api?username=principle105&count_private=true&theme=react&line_height=33)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=principle105&theme=react&hide=Tcl,C)
  [![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=principle105&theme=react)](https://git.io/streak-stats)
</details>
