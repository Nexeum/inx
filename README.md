## INX 

## Installation
1. Git clone the repository and then navigate to the root of the project.
```rust
git clone https://github.com/Nexeum/INX.git

cd syncode
```
2. Run the following command to build and install the binary.
```rust
cargo install --path .
```
For Unix-like systems (Linux, MacOS)

- Bash(Linux): Add to ~/.bashrc or ~/.bash_profile

```rust
export PATH="$HOME/.cargo/bin:$PATH"
```

- Zsh (macOs): Add to ~/.zshrc:

```rust
export PATH="$HOME/.cargo/bin:$PATH"
```

After adding the line, apply the changes:

```rust
source ~/.bashrc  # or source ~/.zshrc
```

- Windows: Add C:\Users\<YourUserName>\.cargo\bin to your system's PATH environment variable.

## Usage

1. **Initialize a Repository (init):**
- Initialize a repository in the current working directory:
```rust
inx init
```
- Or initialize a repository in a different directory:
```rust
inx init <"path/to/another/dir">
```
2. **Clone a Repository (clone):**
- Clone a repository to the current working directory:
```rust
inx clone <"path/to/source/repo">
```
- Or clone a repository to a different directory:
```rust
inx clone <"path/to/source/repo"> <"path/to/destination/repo">
```
3. **Add Files to Tracking (add):**
- Add files to be tracked:
```rust
inx add file1.txt file2.txt
```
4. **Remove Files from Tracking (remove):**
- Remove a file from being tracked:
```rust
inx add file1.txt file2.txt
```
5. **Commit Changes (commit):**
- Commit the current state of the repository:
```rust
inx commit
```
6. **View Repository Status (status):**
- View the status of tracked and untracked files:
```rust
inx status
```
7. **View Commit Log (log):**
- View the commit history:
```rust
inx log
```
8. **View the differences/changes (diff):**
- View the differences/changes between revisions:
```rust
inx diff <"rev1"> <"rev2">
```
9. **View current head/branch (heads):**
- View the current head/branch of the repository:
```rust
inx heads
```
10. **View a file (cat):**
- View the content of a file:
```rust
inx cat <"file.txt">
```
11. **Check out a specific revision (checkout):**
- Check out a specific revision:
```rust
inx checkout <"rev1">
```
12. **Merge 2 different revisions (merge):**
- Merge 2 different revisions:
```rust
inx merge <"rev1"> <"rev2"> <"path/to/repo">
```
13. **Push a commit (push):**
- Push a commit:
```rust
inx push <"remote"> <"local">
```
14. **Pull a commit (pull):**
- Pull a remote repo to local repo:
```rust
inx push <"remote"> <"local">
```
15. **View a help message (help):**
- View the help message:
```rust
inx help
```
