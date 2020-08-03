![FCC Logo](images/fcc-logo.svg)

# 💥 Welcome to freeCodeCamp Projects

Here are all the projects I developed during my journey through **[freeCodeCamp](https://www.freecodecamp.org/)** certifications.

Each project has its own repository, but they were grouped here using the [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) functionality.

## ⏳ Projects timeline 
**[Click here](https://rhenangarcia.github.io/freecodecamp-projects)** to see my journey through the development of the projects.

## 🗃 Projects list
### Responsive Web Design Certification
* **[tribute-page](https://github.com/rhenangarcia/tribute-page)**

## 🧰 Prerequisites
Make sure you have installed all of the following prerequisites on your machine:
* **[Git](https://git-scm.com/downloads)**.

## 🔧 Install
### Option 1
```sh
$ git clone --recurse-submodules https://github.com/rhenangarcia/freecodecamp-projects
$ cd freecodecamp-projects/
```

### Option 2
```sh
$ git clone https://github.com/rhenangarcia/freecodecamp-projects
$ cd freecodecamp-projects/
$ git submodule update --init --recursive
```

## ⚙️ Usage
* Add modules to repository:
  ```sh
  $ git submodule add SUBMODULE_URL
  $ git commit -am "add SUBMODULE_NAME module"
  $ git push
  ```
* Push changes directly to modules:
  ```sh
  $ cd SUBMODULE_DIR 
  $ git commit -am "COMMIT_MESSAGE"
  $ git push
  $ cd ../
  $ git commit -am "COMMIT_MESSAGE"
  $ git push --recurse-submodules=on-demand
  ```
* Push changes to repository:
  * Option 1
    ```sh
    $ git commit -am "COMMIT_MESSAGE"
    $ git push --recurse-submodules=on-demand
    ```
  * Option 2
    ```sh
    $ git commit -am "COMMIT_MESSAGE"
    $ git push --recurse-submodules=check
    ```
* Update modules to their latest commit:
  ```sh
  $ git submodule update --remote
  ```
* Update repository to lastest commit:
  * Option 1 
    ```sh
    $ git pull --recurse-submodules
    ```
  * Option 2
    ```sh
    $ git pull
    $ git submodule update --init --recursive
    ```

## 👤 Author
* **GitHub: [@rhenangarcia](https://github.com/rhenangarcia)**
* **LinkedIn: [@rhenangarcia](https://linkedin.com/in/rhenangarcia)**

## 🤝 Contributing
Contributions, issues and feature requests are welcome!

## 💓 Support me
Give a ⭐️ if this project helped you!

## 📝 License
This project is [MIT](LICENSE) licensed. 

**Copyright © 2020 [Rhenan Garcia](https://github.com/rhenangarcia).**