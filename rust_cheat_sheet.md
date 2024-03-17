//generate snapshot tests 
    cargo install cargo-insta
    //when left side is already a string
    assert_snapshot!("hello", @"");
    //when left side isn't a string
    assert_display_snapshot!(buffer, @"");
    cargo insta test
    cargo insta review

//talking to a CLI
    cargo run -- --first_argument 123 --second_argument "blablabla" --third_argument 4556

//useful crates
    -tokio //async stuff
    -proptest //tests: Pour rappel le property testing c'est le fait d'écrire un test où l'ont décrit une propriété que le programme doit respecter puis on laisse la librairie de test s'occuper de générer des tests toute seule
    -serde
    -sqlx //sql in rust
    -clap //creating CLI

//create a file
    https://doc.rust-lang.org/stable/std/fs/struct.File.html

