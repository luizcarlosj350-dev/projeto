 git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
PS C:\Users\LuizCarlosGomesdaSil> git branch -M main
PS C:\Users\LuizCarlosGomesdaSil> git remote add origin https://github.com/luizcarlosj350-dev/projetos.git
error: remote origin already exists.
PS C:\Users\LuizCarlosGomesdaSil> git push -u origin main[vx.y.z]
fatal: invalid refspec 'main[vx.y.z]'
PS C:\Users\LuizCarlosGomesdaSil> git add CHANGELOG.md git commit -m "docs: update changelog for uX vX.y.z" git push origin main
error: unknown switch `m'
usage: git add [<options>] [--] <pathspec>...

    -n, --[no-]dry-run    dry run
    -v, --[no-]verbose    be verbose

    -i, --[no-]interactive
                          interactive picking
    -p, --[no-]patch      select hunks interactively
    --[no-]auto-advance   auto advance to the next file when selecting hunks interactively
    -U, --unified <n>     generate diffs with <n> lines context
    --inter-hunk-context <n>
                          show context between diff hunks up to the specified number of lines
    -e, --[no-]edit       edit current diff and apply
    -f, --[no-]force      allow adding otherwise ignored files
    -u, --[no-]update     update tracked files
    --[no-]renormalize    renormalize EOL of tracked files (implies -u)
    -N, --[no-]intent-to-add
                          record only the fact that the path will be added later
    -A, --[no-]all        add changes from all tracked and untracked files
    --[no-]ignore-removal ignore paths removed in the working tree (same as --no-all)
    --[no-]refresh        don't add, only refresh the index
    --[no-]ignore-errors  just skip files which cannot be added because of errors
    --[no-]ignore-missing check if - even missing - files are ignored in dry run
    --[no-]sparse         allow updating entries outside of the sparse-checkout cone
    --[no-]chmod (+|-)x   override the executable bit of the listed files
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character

PS C:\Users\LuizCarlosGomesdaSil> git tag -a vX.Y.Z -m "Release vX.Y.Z" git push origin vX.Y.Z
fatal: too many arguments
PS C:\Users\LuizCarlosGomesdaSil>DB_DRIVE='mysql'
D8_HOST='localshost
DB_NAME='senac'
DB_USERNAME='root'
DB_PASSWORD='123456789'
DB_PORT=''3306
DB_CHARSET='utf-8'










 
