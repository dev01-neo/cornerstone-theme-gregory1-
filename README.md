# dev01-neo
# Git

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.


all git command history
    3  npm install
    4  stencil init
    5  stencil init
    6  stencil init
    7  npm install
    8  stencil start
    9  stencil start
   10  npm install -g @bigcommerce/stencil-cli@3.6.2
   11  npm install
   12  stencil start
   13  node -v
   14  npm -v
   15  stencil -v
   16  stencil --version
   17  stencil init
   18  stencil start
   19  npm install
   20  stencil start
   21  npm rebuild node-sass
   22  stencil start
   23  stencil start
   24  stencil --version
   25  npm install
   26  stencil start
   27  npm rebuild node-sass
   28  npm install
   29  stencil start
   30  stencil start
   31  stencil start
   32  stencil init
   33  stencil start
   34  node -v
   35  nvm install 12.0.0
   36  nvm use 12.0.0
   37  nvm use 12
   38  nvm list
   39  nvm uninstall 12.13.0
   40  nvm use 12
   41  nvm use 12.13.0
   42  nvm use 12.0.0
   43  nvm list
   44  nvm use 12
   45  nvm use 14.18.1
   46  stencil init
   47  stencil start
   48  stencil start
   49  npm clean cache
   50  stencil start
   51  stencil start
   52  stencil init
   53  stencil start
   54  stencil --version
   55  npm install -g @bigcommerce/stencil-cli@3.6.2
   56  stencil init
   57  npm install
   58  npm list
   59  nvm list
   60  node --version
   61  npm --version
   62  stencil start
   63  stencil start
   64  npx create-react-app my-app
   65  cd ..
   66  ls
   67  del delete/
   68  rmdir delete/ /s
   69  rmdir delete/ /f
   70  rmdir delete
   71  rmdir delete /s
   72  rmdir delete /r
   73  rmdir delete s
   74  rmdir delete /s
   75  rmdir delete /f
   76  rmdir delete /d
   77  rmdir /s delete/
   78  rmdir s delete/
   79  git clone https://github.com/dev01-neo/Bigcommerce-NextJs-Prismic.git
   80  git clone https://github.com/dev01-neo/Bigcommerce-NextJs-Prismic.git
   81  git --version
   82  git clone https://github.com/dev01-neo/Bigcommerce-NextJs-Prismic.git
   83  git clone https://github.com/dev01-neo/Bigcommerce-NextJs-Prismic.git
   84  code .
   85  git branch
   86  git branch
   87  git switch -h
   88  git switch neodevelop
   89  git switch compare-page 
   90  git branch -D compare-page
   91  git branch -d compare-page
   92  git switch neodevelop
   93  git branch -d compare-page
   94  git switch neodevelop
   95  git checkout -b compare-page neodevelop 
   96  git switch neodevelop
   97  git branch -d compare-page
   98  git branch -b compare-page neodevelop 
   99  git branch 
  100  git branch -h
  101  git switch -c compare-page neodevelop
  102  git switch neodevelop
  103  git switch compare-page
  104  git status -h
  105  git status -b
  106  git switch neodevelop
  107  git status -b
  108  git switch compare-page
  109  git status -h
  110  git branch -h
  111  git branch -a
  112  git lg
  113  git log --graph --pretty=oneline --abbrev-commit
  114  git log
  115  git config --global alias.lgb "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset%n' --abbrev-commit --date=relative --branches"
  116  git config --global alias.lgb "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset%n' --abbrev-commit --date=relative --branches"
  117  git lgb
  118  git lg
  119  git log
  120  git lgs
  121  git lgb
  122  git lgs
  123  git ifs -h
  124  ifs -h
  125  git -h
  126  git config
  127  git config --global --unset-all
  128  git config --global --unset-all
  129  git config --global --unset mysteriouscloud
  130  git config --global --unset mysteriouscloud
  131  git config --global user.email jithin.john@neopraxis.in
  132  git config --global user.email "jithin.john@neopraxis.in"
  133  git config --list
  134  git config --global user.name "dev01-neo"
  135  git config --list
  136  git config --global user.password "NEO$2021$@a"
  137  git config --list
  138  git config --list user.password
  139  git config --list
  140  git clone https://github.com/dev01-neo/Bigcommerce-NextJs-Prismic.git
  141  ls
  142  git commit -m "First commit compare page"
  143  git push -h
  144  git push -u orgin compare-page
  145  git push -u orgin master
  146  git auth login
  147  gh auth login
  148  $ ssh-keygen -t ed25519 -C "jithin.john@neopraxis.in"
  149  $ ssh-keygen -t ed25519 -C "jithin.john@neopraxis.in"
  150  ssh-keygen -t ed25519 -C "jithin.john@neopraxis.in"
  151  git push -u orgin compare-page
  152  git push -u orgin master
  153  eval "$(ssh-agent -s)"
  154  ssh-add ~/.ssh/id_ed25519
  155  clip < ~/.ssh/id_ed25519.pub
  156  git push -u orgin compare-page
  157  git push -u orgin master
  158  git push -u orgin master
  159  git status
  160  git branch
  161  git status
  162  clip < ~/.ssh/id_ed25519.pub
  163  git branch 
  164  git branch -a
  165  cd Bigcommerce-NextJs-Prismic/
  166  git branch all
  167  git branch -D all
  168  git branch -a
  169  git branch
  170  git branch
  171  git branch -a
  172  git branch -D compare-page 
  173  git branch main 
  174  git switch main 
  175  git branch -a
  176  git branch -D compare-page 
  177  git switch main 
  178  git checkout -b compare-page main 
  179  git branch
  180  git status
  181  git add .
  182  git status
  183  git restore --staged package-lock.json
  184  git status
  185  git add .
  186  git commit -h
  187  git commit -m "changed package page api and created compare page"
  188  git status
  189  git push -u orgin compare-page
  190  git config -list
  191  git config --list
  192  git config --unset user.password
  193  git config --list
  194  git config --unset user.password
  195  git config --list
  196  git config --unset NEO021a
  197  git config --unset user.password=NEO021a
  198  git config --remove user.password
  199  git config --list
  200  git config --global --unset NEO021a
  201  git config --global --unset user.password
  202  git config --list
  203  git status
  204  npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/learn-starter"
  205  git clone 
  206  git clone 
  207  git branch
  208  cd commerce/
  209  git branch
  210  git branch -a
  211  git checkout -b compare-page
  212  git branch
  213  git status
  214  git add .
  215  npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/learn-starter"
  216  npm install -g create-react-app
  217  npx create-react-app myapp
  218  git clone https://github.com/dev01-neo/Bigcommerce-NextJs-Prismic.git
  219  git checkout e3471db3ebbf2005b290723b01eab01a41a1898a
  220  git checkout 55b9174 
  221  git checkout e3471db3ebbf2005b290723b01eab01a41a1898a
  222  git checkout e3471db3ebbf2005b290723b01eab01a41a1898a
  223  cd Bigcommerce-NextJs-Prismic/
  224  git checkout e3471db3ebbf2005b290723b01eab01a41a1898a
  225  git branch
  226  git status
  227  git branch compare
  228  git switch compare 
  229  git status
  230  git log
  231  git -h
  232  git push -h
  233  git commit -m "back to oct 15 commit"
  234  git log
  235  git add .
  236  git log
  237  git log
  238  git status
  239  git add .
  240  git status
  241  git commit -m "back to oct 15 commit"
  242  git push
  243  git push compare
  244  git push -u origin main 
  245  git push
  246  git push compare
  247  git push
  248  git log
  249  git log
  250  git sta
  251  git status 
  252  git add.
  253  git commit -m "cofigured working env pac.json"
  254  git status 
  255  git logs
  256  git log
  257  git push origin main 
  258  git log
  259  git push
  260  git status 
  261  git status 
  262  cat compare.tsx
  263  cat pages/compare.tsx
  264  nano pages/compare.tsx
  265  cat pages/compare.tsx
  266  cat pages/compare.tsx
  267  nano pages/compare.tsx
  268  cat pages/compare.tsx
  269  git status 
  270  git diff
  271  git diff -h
  272  git diff pages/compare.tsx
  273  cat pages/compare.tsx
  274  git add .
  275  git status 
  276  git restore --staged 
  277  git restore --staged .
  278  git status 
  279  git add .
  280  git status 
  281  git restore --staged .
  282  git add .
  283  nano pages/compare.tsx
  284  git status 
  285  git diff
  286  git status 
  287  git diff
  288  nano pages/compare.tsx
  289  git diff
  290  git commit -m "created compare page"
  291  git status 
  292  git push
  293  git status 
  294  git log
  295  nano pages/compare.tsx
  296  git log
  297  git add .
  298  git status 
  299  nano pages/compare.tsx
  300  git status 
  301  git diff
  302  git status 
  303  git restore pages/compare.tsx
  304  git status 
  305  git restore --staged pages/compare.tsx
  306  git restore pages/compare.tsx
  307  git status 
  308  nano pages/compare.tsx
  309  git status 
  310  cat pages/compare.tsx
  311  git status 
  312  git status 
  313  git add .
  314  git status 
  315  git status 
  316  git status 
  317  git restore pages/compare.tsx
  318  git status 
  319  git status 
  320  git restore --staged pages/compare.tsx
  321  git status 
  322  git restore --staged pages/compare.js
  323  git status 
  324  git status 
  325  git log
  326  git commit -am --amend "by fazil"
  327  git status 
  328  git --amend -m "more code"
  329  git --ammend -m "more code"
  330  git --ammend "more code"
  331  git -ammend "more code"
  332  ammend -h
  333  git ammend -h
  334  git commit -am "test1"
  335  git add .
  336  git commit -m "test1"
  337  git diff
  338  git status 
  339  git log
  340  git reset --hard e371e0043c7407d9ecbb5bedef6cf4764185941c
  341  git status 
  342  git log
  343  git status 
  344  git status 
  345  git reset --hard 3790f547ada7f300fac8093be46fae740af9eada
  346  git status 
  347  git status 
  348  git log
  349  git reset --hard e371e0043c7407d9ecbb5bedef6cf4764185941c
  350  git log
  351  git status 
  352  git log
  353  git revert HEAD 
  354  git status 
  355  git log
  356  git reset --hard 3790f547ada7f300fac8093be46fae740af9eada
  357  git log
  358  git log
  359  git log
  360  git status 
  361  git reset --hard e371e0043c7407d9ecbb5bedef6cf4764185941c
  362  git status 
  363  git log
  364  git reset --hard 3790f547ada7f300fac8093be46fae740af9eada
  365  git log
  366  git log
  367  git status 
  368  git stash list
  369  git stash
  370  git status 
  371  git stash list
  372  git stash pop
  373  cat pages/compare.tsx 
  374  git stash save dummy
  375  git stash list
  376  git stash pop
  377  git stash save dummy
  378  git stash list
  379  git status 
  380  git stash save dummy
  381  git stash list
  382  git stash pop 0
  383  git stash list
  384  git stash save dummy
  385  git stash pop 1
  386  git diff
  387  git stash pop
  388  git stash save dummy
  389  git stash list
  390  git stash pop
  391  git stash list
  392  git stash pop
  393  git stash list
  394  git stash pop dummy
  395  git stash list
  396  git stash apply dummy
  397  git stash list
  398  git stash pop
  399  git stash list
  400  git stash pop all
  401  git stash pop -a
  402  git stash pop 0
  403  git stash list
  404  git stash list
  405  git stash
  406  git stash list
  407  git stash pop 1
  408  git stash list
  409  git stash pop
  410  git stash list
  411  git stash pop 0
  412  git stash pop 0
  413  git stash pop 0 --force
  414  git stash pop 0 --index
  415  git stash pop 0
  416  git diff
  417  git diff
  418  git status 
  419  git status 
  420  git status 
  421  git pull
  422  git diff
  423  git log
  424  git checkout 3790f547ada7f300fac8093be46fae740af9eada
  425  git log
  426  git diff
  427  git status 
  428  git reset --hard 3790f547ada7f300fac8093be46fae740af9eada3790f547ada7f300fac8093be46fae740af9eada
  429  git reset --hard 3790f547ada7f300fac8093be46fae740af9eada
  430  git status 
  431  git pull
  432  cat pages/Menus.tsx 
  433  git pull
  434  git status 
  435  git status 
  436  git status 
  437  git pull
  438  git status 
  439  git restore pages/compare.tsx
  440  git status 
  441  git log
  442  git log
  443  git reset --hard 8c1166a7e03f5a7bf6141ee3c41e967723a74665
  444  git log
  445  git status
  446  git pull
  447  git status 
  448  git reset --hard 8c1166a7e03f5a7bf6141ee3c41e967723a74665
  449  git status 
  450  git pull
  451  nano pages/compare.tsx 
  452  git logs
  453  git log
  454  git sta
  455  git status 
  456  git diff
  457  git diff
  458  git diff
  459  git diff
  460  git diff
  461  git stash list
  462  git stash list
  463  git diff
  464  git diff
  465  stencil init
  466  stencil init
  467  nvm use 12
  468  nvm --verson
  469  nvm --version
  470  nvm --version
  471  nvm --version
  472  npm --version
  473  python -v
  474  choco install nvm; nvm install 12; nvm use 12
  475  yes
  476  stencil init
  477  stencil init
  478  stencil init
  479  stencil start
  480  stencil start
  481  git diff
  482  stencil start
  483  stencil start
  484  rmdir themes/ /s
  485  rmdir themes/ -s
  486  rmdir themes /s
  487  rmdir themes \s
  488  rmdir themes/
  489  nano samle.py
  490  npm install
  491  npm install
  492  git status
  493  git stash list
  494  history >> history.txt
  495  git staus
  496  git status
  497  git reset assets/dist/report.html
  498  git rm --cached assets/dist/report.html
  499  git status
  500  git log
  501  git status
  502  history >> history.txt
    7  history >> history.txt
       git push -u origin main
       echo "# dev01-neo" >> read.md