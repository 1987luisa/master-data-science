    1  exit
    2  dnf search liquidprompt
    3  ls
    4  df -h
    5  sudo systemctl stop network.target
    6  sudo systemctl stop postgresql.service
    7  mount
    8  sudo mount -o ro,remount /dev/mapper/fedora-root
    9  ps aux | more
   10  sudo systemctl stop NetworkManager.service 
   11  sudo mount -o ro,remount /dev/mapper/fedora-root
   12  sudo systemctl stop system-postgresql.slice
   13  sudo mount -o ro,remount /dev/mapper/fedora-root
   14  ps aux | more
   15  sudo systemctl stop avahi-daemon.service
   16  sudo systemctl stop firewalld.service
   17  sudo dnf install zerofree
   18  sudo mount -o ro,remount /dev/mapper/fedora-root
   19  sudo systemctl stop rtkit-daemon.service
   20  sudo mount -o ro,remount /dev/mapper/fedora-root
   21  sudo killall dhclient
   22  sudo mount -o ro,remount /dev/mapper/fedora-root
   23  {lsof +L1; lsof | sed -n '/SYSV/d; /DEL\|(path /p;)}
   24  {lsof +L1; lsof | sed -n '/SYSV/d; /DEL\|(path /p;'}
   25  sudo systemctl stop kdm.service
   26  sudo mount -o ro,remount /dev/mapper/fedora-root
   27  sudo systemctl stop systemd-user-sessions.service
   28  sudo mount -o ro,remount /dev/mapper/fedora-root
   29  ps aux 
   30  kill 2974
   31  sudo kill 2974
   32  sudo kill 2968
   33  sudo mount -o ro,remount /dev/mapper/fedora-root
   34  sudo kill 4084
   35  ps
   36  ps aux
   37  sudo kill 908
   38  sudo kill 907
   39  sudo systemctl stop polkit.service
   40  sudo mount -o ro,remount /dev/mapper/fedora-root
   41  ps aux 
   42  sudo kill 745
   43  sudo systemctl stop dbus.service
   44  ps aux
   45  sudo systemctl stop alsa-state.service
   46  sudo kill 704
   47  sudo mount -o ro,remount /dev/mapper/fedora-root
   48  zerofree /dev/mapper/fedora-root
   49  poweroff
   50  sudo dnf install dolphin util-linux-user
   51  cd Data
   52  cd ..
   53  cd Repositories
   54  cd data-science-toolbox
   55  cd ..
   56  ł
   57  pwd
   58  git
   59  git 
   60  git clone https://github.com/hguadalupe/master-data-science.git
   61  ls
   62  cd master-data-science
   63  ls
   64  cat README.md
   65  kwrite README.md
   66  git status
   67  git add
   68  git add .
   69  git commit
   70  git push
   71  cd
   72  kwrite .git
   73  kwrite .gitconfig
   74  cd -
   75  ls
   76  git status
   77  git log
   78  git pull
   79  git log
   80  kwrite README.md
   81  git add .
   82  git commit -m "Ole, todo genial."
   83  git status
   84  git log
   85  git push
   86  git log
   87  whoami
   88  echo"holahola"
   89  echo "comeon"
   90  cd .
   91  cd ..
   92  cd 
   93  whoami
   94  cat Data/shell/Text_example.txt
   95  cd .ssh
   96  cd ..
   97  cd .ssh
   98  ls -a
   99  ls-a
  100  ls -a
  101  history -5
  102  history -10
  103  cd
  104  ll
  105  alias
  106  cd -
  107  ~
  108  cd ~
  109  cd Repositories
  110  cd master-data-science
  111  ls
  112  ll
  113  CD ~
  114  cd ~
  115  mkdir
  116  kdir dirprueba/subprueba/subsubprueba
  117  kdir -p dirprueba/subprueba/subsubprueba
  118  mkdir -p dirprueba/subprueba/subsubrpueba
  119  touch dirprueba/texto.txt
  120  cp dirprueba/texto.txt dirprueba/subprueba/texto2.txt
  121  ls dirprueba
  122  ls subprueba
  123  ls dirprueba/subprueba
  124  ll dirprueba
  125  cp -r dirprueba dirprueba/subprueba/subsubprueba
  126  cp -rp dirprueba durprueba/subprueba/subsubprueba ./
  127  cp -rp dirprueba dirprueba/subprueba/subprueba ./
  128  cp -rp ./dirprueba ./dirprueba/subprueba/subsubprueba
  129  cp -r dirprueba ./dircopia
  130  ls
  131  rm dircopia
  132  rm -f dircopia
  133  rm -r dircopia
  134  mkdir first_dir
  135  touch firstdir/text_file.txt
  136  cd first_dir
  137  touch text_file.txt
  138  chmod g+r,o+w text_file.txt
  139  ll
  140  chmod g+r,o+w text_file.txt
  141  mkdir sub1
  142  mkdir sub2
  143  mkdir text_file
  144  cp -r text_file.txt sub1/
  145  ls sub 1
  146  ls sub1
  147  mv -p text_file.txt sub2/text_file.txt.2
  148  mv text_file.txt sub2/text_file.txt.2
  149  cp -r sub1 sub3
  150  ls
  151  mv sub3/text_file.txt sub3/text_file.txt.backup
  152  ls sub3
  153  mv sub3/text_file.txt.backup ../.text_file.txt.backup
  154  ls
  155  cd .
  156  ls .
  157  ls -a
  158  mv ../.text_file.txt.backup ./.text_file.txt.backup
  159  ls -a
  160  man
  161  man1
  162  man 1
  163  man CAT
  164  cd ..
  165  cd Data/
  166  man less cad
  167  less 
  168  less shell/Finn.txt
  169  less opentraveldata/optd_aircraft.csv
  170  help tree
  171  man tree
  172  tree
  173  cd
  174  tree -L
  175  man tree
  176  tree -L 2
  177  man less
  178  fsd
  179  fssfasdf f
  180  f ef
  181  sudo systemctl stop system-postgresql.slice
  182  cd Data/shell
  183  ls
  184  cad -n Text_example.txt
  185  cat -n Text_example.txt
  186  cat -n Text_example.txt > Text_example_with_num.txt
  187  cat Text_example_with_num.txt
  188  cat Text_example_with_num.txt >>Text_example_with_num.txt
  189  cat Text_example.txt >>Text_example_with_num.txt
  190  cat Text_example_with_num.txt
  191  cat -n Text_example.txt -n Text_example.txt >> Prueba_Concatena_Varios.txt
  192  cat Prueba_Concatena_Varios.txt
  193  ls
  194  rm Prueba_Concatena_Varios.txt
  195  rm Text_example_with_num.txt
  196  ls
  197  cd
  198  cd Repositories
  199  ls
  200  cd
  201  cd Data/shell
  202  wc
  203  cd Data/shell
  204  cat Text_example.txt | wc 
  205  cat Text_example.txt| head
  206  cat -n Text_example.txt| head -15
  207  cat -n Text_example.txt| head -3
  208  cat -n Text_example.txt| tail -3  head -3 
  209  cat -n Text_example.txt| tail 3  head -3 
  210  cat -n Text_example.txt | tail 3  head -3 
  211  cat -n Text_example.txt | tail -n 3  head -3 
  212  cat -n Text_example.txt | tail -n 1  head -3 
  213  cat -n Text_example.txt | tail -n 1 
  214  cat -n Text_example.txt | tail -n 2 
  215  cat -n Text_example.txt | tail 2 
  216  cat -n Text_example.txt | tail -2 
  217  cat -n Text_example.txt | head -2  tail -2 
  218  cat -n Text_example.txt | head -3 
  219  cat -n Text_example.txt | head -n -3 
  220  cat -n Text_example.txt | head 3 
  221  cat -n Text_example.txt | head -n 3 -n/c 3
  222  cat -n Text_example.txt | head -n 3 | tail -2
  223  cat -n Text_example.txt
  224  cat -n Text_example.txt | head -n 3 | tail -n-3
  225  cat -n Text_example.txt | head -n +3 | tail -n -3
  226  cat -n Text_example.txt | tail -n +3 | head -n -3
  227  cd
  228  ls Data/shell
  229  ls Repositories/master-data-science
  230  cd Repositories/master-data-science
  231  hist
  232  history -100
  233  history -200
  234  history -200 > History_of_commands.md
  235  ls
  236  add.
  237  add. History_of_commands.md
  238  add History_of_commands.md
  239  less History_of_commands.md
  240  ll
  241  git add
  242  git add .
  243  git commit
  244  git push
  245  History -250
  246  history -300
  247  history > History_of_commands.md
  248  cat History_of_commands.md
  249  history -300
  250  history -300 > History_of_commands.md
  251  git add
  252  git add.
  253  git add .
  254  git commit .
  255  git push
  256  cd
  257  find -maxdepth 1 -mmin 300
  258  echo find -maxdepth 1 -mmin 300
  259  find .  -maxdepth 1 -mmin 300
  260  find .  -maxdepth 5 -mmin 300
  261  find ./  -maxdepth 5 -mmin 300
  262  find -./  -maxdepth 5 -mmin 300
  263  find . iname "Text*"
  264  cat .history
  265  blocksearch
  266  cd Repositories/master-data-science
  267  cd
  268  cd Downloads
  269  man mv
  270  mv -t ../Repositories/OldStuff/Joy ./PDF_searcher.py PyFlashyroom.py rotating_bar.py tkinter4.py
  271  alias 
  272  blocksearch
  273  man blocksearch
  274  help blocksearch
  275  mkdir ../Repositories/OldStuff/Joy
  276  mkdir ./Repositories/OldStuff/Joy
  277  mkdir ./Repositories/OldStuff
  278  mkdir Repositories/OldStuff
  279  cd
  280  mkdir Repositories/OldStuff
  281  mkdir ./Repositories/OldStuff/Joy
  282  cd Downloads
  283  mv -t ../Repositories/OldStuff/Joy ./PDF_searcher.py PyFlashyroom.py rotating_bar.py tkinter4.py
  284  ls
  285  cd
  286  cd Repositories/OldStuff/Joy
  287  ls
  288  kwriter
  289  kwrite
  290  cd .. 
  291  cd..
  292  cd ..
  293  cd master-data-science
  294  cd
  295  cd Repositories
  296  cp ./Oldstuff ../Eraseoldstuff
  297  cp ./OldStuff ../Eraseoldstuff
  298  cp -r ./OldStuff ../Eraseoldstuff
  299  cd
  300  cd Repositories/master-data-science
  301  git add .
  302  git push
  303  cd ..
  304  git push .
  305  cd OldStuff
  306  git push
  307  git push .
  308  git pull
  309  git pull .
  310  cd
  311  cd Repositories
  312  cd Repositories/
  313  git clone https://github.com/hguadalupe/OldStuff.git
  314  rm -f OldStuff
  315  rm OldStuff
  316  rm -f -r OldStuff
  317  git clone https://github.com/hguadalupe/OldStuff.git
  318  ls
  319  mv ../Eraseoldstuff ./OldStuff
  320  ls
  321  cd OldStuff
  322  ls
  323  mv -t ./ Eraseoldstuff/Joy Eraseoldstuff/Work
  324  ls
  325  ls Eraseoldstuff
  326  cd Eraseoldstuff
  327  ls
  328  cd ..
  329  rm -f -r Eraseoldstuff
  330  ls
  331  ls Work
  332  cd Work
  333  kwrite param_bulk_renamer.py
  334  cd ..
  335  cd master-data-science
  336  ls
  337  history
  338  cat history
