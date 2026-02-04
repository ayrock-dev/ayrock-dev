```
fn main() {
    let ayrock = Human {
        name: "eric lee"
        role: "product engineer",
        company: "discord",
        location: "san diego, ca",
        languages: vec!["typescript", "rust", "elixir", "lua"],
        editor: "neovim",
        twitter: "https://x.com/ItsAyrock",
    };

    println!("whoami \n\n{:#?}", ayrock);
}
```
