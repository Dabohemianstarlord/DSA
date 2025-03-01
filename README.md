# Data Structures and Algorithm
Data structure and Algorithm (DSA)

## Contribution Guidelines

### 1. Contribution Specifications

The problem being contributed must either be a simple **file** (**Eg.** [`kruskal-algorithm.cpp`](https://github.com/MakeContributions/DSA/blob/main/graphs/c-or-cpp/kruskal-algorithm.cpp), [`linear-search.java`](https://github.com/MakeContributions/DSA/blob/main/searching/java/linear-search.java)) or a more complex **directory** ([`palindrome/`](https://github.com/MakeContributions/DSA/tree/main/strings/rust/palindrome)). This is a unit `problem`.

The directory tree has the following convention of `category/language/problem`, where `category` is the topic or category of the  problem being contributed (**Eg.** `strings`, `sorting`, `linked-lists` etc.), `language` represents the language code of the problem (**Eg.** `c-or-cpp` for C/C++, `python` for Python, `java` for Java etc.), and `problem` is a conforming name to the problem (**Eg.** `linear-search.cpp`, `palindrome`, `queue-linked-list.cpp` etc.)

A unit `problem` must conform to the following specifications:
- The name should be in lowercase. (**Eg.** `palindrome/`, `binary-search.cpp` etc.).
- Each word must be seperated by a **dash** or a **hyphen** (`-`).

**If you have a problem that belongs to a new *topic* or *category* than one which are present:**
1. Create a new folder and an index for it inside (a readme, `README.md` file).
2. To each new index file, write the readme with your `problem` in it ([Markdown Documentation](https://guides.github.com/features/mastering-markdown/)).
3. The folder name can also only contain **lowercase characters** and **dashes** or **hyphens** (`-`) (Eg. `strings` `sorting` etc.)

#### Simple (File) Contributions

The file should conform to the `problem` specification, and the extension (**Eg.** `linear-search.java`, `kruskal-algorithm.cpp`, `count-inversions.js` etc.)

#### Project/Folder-based Contributions

The project and folder-based contributions have a bit more stricter contribution contribution specifications.

The folder should conform to the `problem` specification, along with the following specifications

**Folder Structure**
```bash
problem-name\
| - .gitignore
| - README.md
| - Makefile       # or the specific specification/requirements/configuration file
| - src\
    | - main.ext
```

#### `README.md` Specification / Template

```markdown
# <Title of the Problem>

< description of the problem >

## Prerequisites

- prerequisite library or package
- [prerequisite library](https://www.example.com/link-to-official-library)

## Instructions

- instructions to run the project
- < Simple and reproducible commands to execute the project >
    ```bash
     make # or 'cargo run', or 'dotnet run' or 'mvn exec:java' etc.
    ```
## Test Cases & Output < if exists>

< If you can provide test cases, describe it here, else remove this section >
```

#### `.gitignore` File
```gitignore
# add all output files and build files to be excluded from git tracking
main     # executable file also must have the project name
target/  # the build file, for example for rust
```

#### Build File / Specification File / Configuration File
It can be any of the following ones
- **C/C++**: `Makefile`
- **Python**: `requirements.txt`
- **JavaScript**: `package.json` and `package-lock.json`
- **Rust**: `Cargo.toml` and `Cargo.lock`
- **Go**: `go.mod`

#### Source Code File

The source code files, should either be in `src/` folder (**Eg.** `src/main.cpp` or `src/main.js`) or the root folder (**Eg.** `palindrome.go` or `App.java`) where `ext` is the file extension for the specific programming language.

Again, the source codes must conform to a valid file structure convention that the programming language enforces.

### 2. Naming Convention

The programming should keep the naming convention rule of each programming language.

### Other topic
- [First-time contribution](CONTRIBUTING.md)

## Contributors
<a href="https://github.com/MakeContributions/DSA/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=MakeContributions/DSA" />
</a>

## License
[MIT](./LICENSE)
