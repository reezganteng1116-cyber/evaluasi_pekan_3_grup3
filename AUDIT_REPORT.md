
Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ git mv arrow_left.png \images
fatal: Unable to create 'C:/Users/Baja Malik/OneDrive/Documents/evaluasi_pekan_3_grup3/.git/index.lock': File exists.

Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ ls -la .git | grep index.lock
-rw-r--r-- 1 Baja Malik 197609 25201 Aug 22 09:03 index.lock

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ rm -f .git/index.lock

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ ls -la .git | grep index.lock

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ history
    1  mkdir -p legacy_portfolio_dump/{img,assets,versi,sementara}
    2  touch legacy_portfolio_dump/{index_lama.html,contact_us.html,style.css,main.js,notes.txt,README.md,logo.png}
    3  touch legacy_portfolio_dump/img/background_old.jpg
    4  touch legacy_portfolio_dump/assets/{header.png,logo.svg,footer_script.js}
    5  touch legacy_portfolio_dump/versi/{index_v1.html,old_style.css}
    6  touch legacy_portfolio_dump/sementara/{temp_draft.html,data_test.txt}
    7  echo "<h1>Homepage Lama</h1>" >> legacy_portfolio_dump/index_lama.html
    8  tree legacy_portfolio_dump
    9  cat my_portfolio_professional/public/index.html
   10  mkdir -p my_portfolio_professional/{public/{css,js,assets/images},src,docs,temporary_storage}
   11  echo "<h1>Homepage Lama</h1>" >> legacy_portfolio_dump/index_lama.html
   12  mkdir -p legacy_portfolio_dump/{img,assets,versi,sementara}
   13  touch legacy_portfolio_dump/{index_lama.html,contact_us.html,style.css,main.js,notes.txt,README.md,logo.png}
   14  touch legacy_portfolio_dump/img/background_old.jpgAAAA
   15  touch legacy_portfolio_dump/assets/{header.png,logo.svg,footer_script.js}
   16  touch legacy_portfolio_dump/versi/{index_v1.html,old_style.css}
   17  touch legacy_portfolio_dump/sementara/{temp_draft.html,data_test.txt}
   18  mkdir
   19  mkdir Baja
   20  <h1>Homepage Lama</h1>
   21  echo "Hello, Bash!"~
   22  bash hello.sh
   23  Hello, Bash!
   24  <h1>Homepage Lama</h1>
   25  mkdir -p legacy_portfolio_dump/{img,assets,versi,sementara}
   26  touch legacy
   27  _portfolio_dump/{index_lama.html,contact_us.html,style.css,main.js,notes.txt,README.md,logo.png}
   28  mkdir -p my_portfolio_professional/{public/{css,js,assets/images},src,docs,temporary_storage}
   29  public/assets/images/:
   30  mv -i legacy_portfolio_dump/logo.png my_portfolio_professional/public/assets/images/
   31  ls legacy_portfolio_dump
   32  cat my_portfolio_professional/public/index.html
   33  q
   34  more tugas1day4
   35  mv
   36  mv --help
   37  more tugas1day4
   38  sudo
   39  clear
   40  more tugas1day4
   41  ls legacy_portfolio_dump
   42  clear
   43  more -d
   44  more -d
   45  clear
   46  grep "html" tugas1day4
   47  grep tspmo~
   48  mkdir tes
   49  grep new
   50  grep 'shell' new
   51  grep new
   52  echo "tes woi"
   53  cat new.txt
   54  cd testtugas ls
   55  bash --version~
   56  bash --version
   57  ls
   58  cd
   59  pwd
   60  echo halo gusy
   61  #!/bin/bash
   62  trash=~/TRASH
   63  if [ ! -e $trash ]; then   mkdir $trash; elif [ ! -d $trash ]; then   echo "$0: error: $trash is not a directory"; exit 1; fi
   64  while getopts "hr:t:s:u:" options; do case $options in shift $((OPTIND-1))
   65  while [ $# -gt 0 ]; do   if [ ! -e $1 ]; then     echo "$0: error: tried to delete file that does not exist: $1";     shift;     continue;   fi;   tarname="$1.tar";   tar -cf "$tarname" "$1";   mv "$tarname" $trash;   rm -rf "$1";   shift; done
   66  | tee -a file.log~
   67  mv file.log public
   68  mv file.log~ public
   69  mv file.log
   70  mv access.log~ logs
   71  mv error.log~ logs
   72  mv server.log logs
   73  mv server.log~ logs
   74  ls
   75  for server.log~ in logs/*.log; do grep
   76  for server.log~ in logs/*.log; do clear;
   77  bash scripts/analyze_logs.sh
   78  cd my_portofolio_prefesional/src
   79  cd src
   80  nano analyze_logs.sh
   81  chmod +x analyze_logs.sh~
   82  ./analyze_logs.sh
   83  #!/bin/bash
   84  cd "$(dirname "$0")/.."
   85  REPORT_FILE="server_issues_report.txt"
   86  > "$REPORT_FILE"
   87  for logfile in logs/*.log; do     grep -inE "ERROR|Failed|Warning" "$logfile" | while read -r line; do         echo "$logfile: $line" >> "$REPORT_FILE";     done; done
   88  ERROR_COUNT=$(grep -io "ERROR" logs/server.log | wc -l)
   89  echo "" >> "$REPORT_FILE"
   90  echo "Total Kesalahan di server.log: $ERROR_COUNT" >> "$REPORT_FILE"
   91  echo "Selesai! Hasil di $REPORT_FILE"c
   92  ./analyze_llogs.sh
   93  ./analzye_logs.sh
   94  dater.exe
   95  Apphlpdm.dll                                                             dirmngr-client.exe
   96  ApplicationControlCSP.dll                                                dirmngr.exe
   97  ApplicationFrame.dll                                                     dirname.exe
   98  ApplicationFrameHost.exe                                                 dirs
   99  git remote add origin https://github.com/astrNVlik/rumahit-git.git
  100  git remote add origin https://github.com/astrNVlik/rumahit-git.git
  101  git remote add origin https://github.com/astrNVlik/rumahit.git
  102  git remote add origin https://github.com/astrNVlik/rumahit.git
  103  git branch -m main
  104  git push -u origin main
  105  git pull
  106  git init
  107  git push
  108  git git remote add origin https://github.com/astrNVlik/rumahit.git
  109  git remote add origin https://github.com/astrNVlik/rumahit.git~
  110  git remote add https://github.com/astrNVlik/rumahit.git
  111  clear
  112  git remote add https://github.com/astrNVlik/rumahit.git
  113  git remote add https://github.com/astrNVlik/rumahit.git
  114  ls
  115  git remote add https://github.com/astrNVlik/rumahit.git
  116  git remote add https://github.com/astrNVlik/rumahit.git
  117  -f
  118  git branch feature/login
  119  git branch
  120  git branch hello-world-image
  121  git checkout
  122  git checkout
  123  git status
  124  git add .
  125  echo "hello world" > index.html
  126  git add .
  127  echo "tambah deskripsi project" >>
  128  echo "tambah deskripsi" >> index.html
  129  cat
  130  lg
  131  ls
  132  git log --oneline
  133  git status
  134  echo "hello world!"
  135  echo "hello word
  136  git
  137  git log
  138  echo
  139  git revert
  140  git revert HEAD
  141  revert HEAD
  142  git add .
  143  git commit
  144  git remote add origin https://github.com/astrNVlik/rumahit.git
  145  clear
  146  car
  147  cat
  148  git log
  149  git add https://github.com/astrNVlik/rumahit.git
  150  mkdir revert
  151  git add https://github.com/astrNVlik/rumahit.git
  152  git add https://github.com/astrNVlik/rumahit.git
  153  git remote add https://github.com/astrNVlik/rumahit.git
  154  git remote add origin https://github.com/astrNVlik/rumahit.git
  155  git push -u origin main
  156  git remote add origin https://github.com/astrNVlik/rumahit.git
  157  sudo apt git
  158  ls
  159  mkdir test
  160  help
  161  select index.html
  162  git log
  163  clear
  164  ls
  165  cd
  166  git help
  167  clear
  168  git
  169  clear
  170  mkdir github test
  171  mkdir github_test
  172  clear
  173  cd  gittesting
  174  cd Documents\codingv3\gittesting
  175  cd Documents
  176  git clone
  177  cd clone https://github.com/astrNVlik/html-css
  178  cd clone https://github.com/astrNVlik/html-css
  179  clear
  180  cd clone https://github.com/astrNVlik/html-css
  181  git status
  182  git status
  183  mkdir githubtest
  184  git remote add origin https://github.com/astrNVlik/rumahit-git85.git
  185  git help
  186  git init
  187  git remote add origin https://github.com/astrNVlik/rumahit-git85.git
  188  git remote -v
  189  git status
  190  git add .
  191  git add .
  192  git status
  193  git commit
  194  git push
  195  git push
  196  git push -u
  197  git push --set-upstream
  198  git help
  199  git push -u
  200  git branch -M main
  201  git push -u origin main
  202  git push -u origin main
  203  git remote add origin https://github.com/astrNVlik/rumahit-git85.git~
  204  git remote -d
  205  git remote -d https://github.com/astrNVlik/rumahit-git85.git
  206  git remote -v
  207  git remote remove https://github.com/astrNVlik/rumahit
  208  git remote remove https://github.com/astrNVlik/rumahit-git
  209  git remote remove origin
  210  git remove -v
  211  git remote -v
  212  git remote add origin https://github.com/astrNVlik/rumahit-git85.git
  213  git push
  214  git push -u origin main
  215  git clone https://github.com/astrNVlik/html-css
  216  git status
  217  git status
  218  git clone
  219  git clone https://github.com/astrNVlik/html-css
  220  ls
  221  cd html-css
  222  code .
  223  git add .
  224  git commit -m "mie ayam"
  225  git push
  226  git status
  227  git commit -am "Tmbah File biodata"
  228  clear
  229  git push origin fitur_baja
  230  git push .
  231  ls
  232  rm -r
  233  cat
  234  cat pitch_deck.html
  235  cd ..
  236  git add origin -u script.js
  237  git add script.js
  238  git remote add https://github.com/lexx-project/loginPage
  239  git remote add origin https://github.com/lexx-project/loginPage
  240  git code .
  241  git.
  242  clear
  243  git checkout -b js
  244  git init
  245  git checkout -b js
  246  git remote add origin https://github.com/lexx-project/loginPage.git
  247  git push
  248  git push -u origin js
  249  git status
  250  git add .
  251  git init -m .
  252  git commit -m "Add script js"
  253  git push -u origin js
  254  git pull
  255  git push -u origin js
  256  git pull -u js
  257  git pull origin js
  258  cd ..
  259  mkdir javascript
  260  cd
  261  cd -
  262  cd javascript
  263  git clone
  264  git clone https://github.com/lexx-project/loginPage~
  265  git clone https://github.com/lexx-project/loginPage.git
  266  cd loginPage/
  267  git checkout -b js
  268  ls
  269  git status
  270  git help
  271  git help -a
  272  code .
  273  git add .
  274  git commit .
  275  git commit -m "add script js"
  276  git push
  277  git push -u
  278  git push -u origin js
  279  git push .
  280  git pull origin main
  281  git checkout js
  282  git push .
  283  git force
  284  git -help
  285  give --help
  286  git --help
  287  git -D checkout
  288  git checkout js
  289  git checkout .
  290  git checkout js]
  291  git pull origin main
  292  git checkout js
  293  git merge main
  294  git push -u origin js
  295  git push -u origin js
  296  clear
  297  cd
  298  git push
  299  git push origin fitur_baja
  300  git remote
  301  git push -u origin test_baja
  302  clear
  303  git status
  304  git status
  305  git clone https://github.com/astrNVlik/evaluasi_pekan_3_grup3
  306  ls
  307  code .
  308  code .
  309  cat
  310  ls
  311  git status
  312  git branch -a
  313  git log
  314  tree -L
  315  tree -L 2
  316  git log
  317  git log --all --full history--
  318  git log --all --full-history -- "/debug.log"
  319  git log --all --full-history -- /debug.log
  320  git grep .
  321  git checkout
  322  git checkout .
  323  git checkout -b hotfix-cleanup
  324  mkdir -p assets/images
  325  ls
  326  git mv whatsapp-icon.png assets/images/
  327  git rm debug.log
  328  git commit .
  329  git mv arrow_left.png \images
  330  ls -la .git | grep index.lock
  331  rm -f .git/index.lock
  332  ls -la .git | grep index.lock
  333  history

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ ls -R
.:
24-7-support.png    TESTING.md          banner-old.jpg        dark-theme.css      hero-image.jpg      logs/             payment-methods.jpg    run-tests.bat       star-filled.png   testimonial3.jpg
404.html            TROUBLESHOOTING.md  banner.jpg            database.log        home.html           main.css          payment.log            run-tests.sh        start-server.bat  theme.css
API.md              USER_GUIDE.md       bg.jpg                delivery-truck.jpg  ideas.md            main.html         performance.log        scripts/            start-server.sh   todo.md
ARCHITECTURE.md     about.html          bootstrap.css         deploy.bat          images/             maintenance.html  phone-icon.png         search-icon.png     stop-server.bat   twitter-icon.png
BACKUP_RESTORE.md   access.log          bugs.md               deploy.log          img/                maintenance.log   photos/                security-badge.png  stop-server.sh    uninstall.bat
CHANGELOG.md        api.log             build.bat             deploy.sh           index-old.html      meeting-notes.md  pics/                  security.log        style.css         uninstall.sh
CODE_OF_CONDUCT.md  app.css             build.sh              design-notes.md     index.html          menu-icon.png     product.html           seed-data.bat       styles/           update.bat
CONTRIBUTING.md     application.log     cache.log             docs/               index_backup.html   migrate.bat       product1-thumb.png     seed-data.sh        styles.css        update.sh
DATABASE_SCHEMA.md  archive/            cart-icon.png         documentation/      info-icon.png       migrate.sh        product1.jpg           server.log          system.log        user-activity.log
DEPLOYMENT.md       archive.md          check-icon.png        draft.md            instagram-icon.png  mobile.css        product2-thumb.png     session.log         tablet.css        user-icon.png
DEVELOPER_GUIDE.md  arrow-down.png      clean-cache.bat       email-icon.png      install.bat         money-back.png    product2.jpg           setup.bat           team-member1.jpg  utilities.css
FAQ.md              arrow-left.png      clean-cache.sh        email.log           install.sh          monitoring.bat    product3-thumb.png     setup.sh            team-member2.jpg  warehouse-photo.jpg
INSTALL.md          arrow-right.png     close-icon.png        error-icon.png      landing.html        monitoring.sh     product3.jpg           sidebar.html        team-member3.jpg  warning-icon.png
LICENSE.md          arrow-up.png        coming-soon.html      error.html          layout.css          navbar.html       products.html          slide1-mobile.jpg   temp/             webhook.log
MIGRATION_GUIDE.md  assets/             components.css        error.log           linkedin-icon.png   normalize.css     project-timeline.md    slide1.jpg          temp-notes.md     youtube-icon.png
MONITORING.md       background.jpg      compress-images.bat   facebook-icon.png   links.md            notes.md          quality-guarantee.png  slide2-mobile.jpg   temp-style.css
PERFORMANCE.md      backup/             compress-images.sh    fast-delivery.png   location-icon.png   notification.log  references.md          slide2.jpg          temp.html
README-backup.md    backup-docs.md      contact.html          features.md         login.html          office-photo.jpg  register.html          slide3-mobile.jpg   test.bat
README.md           backup-files.bat    cron.log              footer.html         logo-backup.png     old-docs.md       requirements.md        slide3.jpg          test.html
README_old.md       backup-files.sh     css/                  graphics/           logo-copy.png       old-style.css     reset.css              sms.log             test.sh
SECURITY.md         backup-style.css    custom.css            header.html         logo.png            optimize.bat      resources.md           specifications.md   testimonial1.jpg
STUDENT_TASK.md     backup.log          customer-service.jpg  hero-bg.jpg         logo_old.png        optimize.sh       responsive.css         star-empty.png      testimonial2.jpg

./archive:
archived-banner.jpg  legacy-logo.png  old-index.html  old-style.css

./assets:
css/  images/

./assets/css:
bootstrap.css  custom.css  main.css

./assets/images:
background.jpg  banner.jpg  hero-image.jpg  icons/  logo.png  whatsapp-icon.png

./assets/images/icons:
facebook-icon.png  instagram-icon.png  twitter-icon.png

./backup:
hero-backup.jpg  index-backup-2024.html  logo-backup.png  old-files/  style-backup.css

./backup/old-files:
index-v1.html  index-v2.html  old-logo.png  style-old.css

./css:
app.css  bootstrap.css  components.css  main.css  mobile.css  responsive.css  style.css  tablet.css  theme.css  utilities.css

./docs:
API.md  DEPLOYMENT.md  README.md  USER_GUIDE.md  project-notes.md

./documentation:
ARCHITECTURE.md  FAQ.md  INSTALL.md  TROUBLESHOOTING.md

./graphics:
24-7-support.png  fast-delivery.png  money-back.png  quality-guarantee.png  security-badge.png

./images:
background.jpg  banner.jpg  hero-image.jpg  logo-old.png  logo.png  product1.jpg  product2.jpg  product3.jpg  thumbnails/

./images/thumbnails:
product1-thumb.png  product2-thumb.png  product3-thumb.png

./img:
bg.jpg  hero-bg.jpg  icons/  logo.png

./img/icons:
facebook-icon.png  instagram-icon.png  twitter-icon.png  whatsapp-icon.png  youtube-icon.png

./logs:
access.log  application.log  debug.log  error.log  server.log  system.log

./photos:
office-photo.jpg  team-member1.jpg  team-member2.jpg  team-member3.jpg  warehouse-photo.jpg

./pics:
slide1.jpg  slide2.jpg  slide3.jpg  testimonial1.jpg  testimonial2.jpg  testimonial3.jpg

./scripts:
backup-files.bat  backup-files.sh  deploy.bat  deploy.sh  setup.bat  setup.sh

./styles:
components.css  dark-theme.css  layout.css  main.css

./temp:
draft.html  temp-page.html  temp-style.css  test-image.jpg

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ git log --oneline -- <path/to/debug.log>
bash: syntax error near unexpected token `newline'

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ git log --newline -- <path/to/debug.log>
bash: syntax error near unexpected token `newline'

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ git log -p -- <path/to/debug.log>
bash: syntax error near unexpected token `newline'

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ move
bash: move: command not found

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ mv *.jpg assets/img\
>
mv: target 'assets/img' is not a directory

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ mv *.jpg >> assets/img
mv: target 'warehouse-photo.jpg' is not a directory

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ mv *.jpg assets

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ cd assets

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets (hotfix-cleanup)
$ mv *.jpg image
mv: target 'image' is not a directory

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets (hotfix-cleanup)
$ mv *.jpg images

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets (hotfix-cleanup)
$ cd evaluasi_pekan_3_grup3
bash: cd: evaluasi_pekan_3_grup3: No such file or directory

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets (hotfix-cleanup)
$ cd ..

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ mv *.png assets

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ cd assets

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets (hotfix-cleanup)
$ mv *.png images

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets (hotfix-cleanup)
$ cd images

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ mv *..-icon icon
mv: cannot stat '*..-icon': No such file or directory

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ mv *.-icon icon
mv: cannot stat '*.-icon': No such file or directory

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ mv *icon.jpg icons
mv: cannot stat '*icon.jpg': No such file or directory

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ mv *cart-icon.png icons

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ mv *icon*.jpg *icon*.png icons/
mv: cannot stat '*icon*.jpg': No such file or directory

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ mv *icon*.jpng icons
mv: cannot stat '*icon*.jpng': No such file or directory

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ mv *icon*.jpg icons
mv: cannot stat '*icon*.jpg': No such file or directory

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ git mv *icon.jpg icons
fatal: bad source, source=assets/images/*icon.jpg, destination=assets/images/icons/*icon.jpg

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ ls
24-7-support.png  background.jpg        delivery-truck.jpg  logo-backup.png  office-photo.jpg     product2.jpg           slide1-mobile.jpg  slide3.jpg        team-member3.jpg
arrow-down.png    banner-old.jpg        fast-delivery.png   logo-copy.png    payment-methods.jpg  product3-thumb.png     slide1.jpg         star-empty.png    testimonial1.jpg
arrow-left.png    banner.jpg            hero-bg.jpg         logo.png         product1-thumb.png   product3.jpg           slide2-mobile.jpg  star-filled.png   testimonial2.jpg
arrow-right.png   bg.jpg                hero-image.jpg      logo_old.png     product1.jpg         quality-guarantee.png  slide2.jpg         team-member1.jpg  testimonial3.jpg
arrow-up.png      customer-service.jpg  icons/              money-back.png   product2-thumb.png   security-badge.png     slide3-mobile.jpg  team-member2.jpg  warehouse-photo.jpg

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ cd icons/

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images/icons (hotfix-cleanup)
$ ls
cart-icon.png   close-icon.png  error-icon.png     info-icon.png       linkedin-icon.png  menu-icon.png   search-icon.png   user-icon.png     whatsapp-icon.png
check-icon.png  email-icon.png  facebook-icon.png  instagram-icon.png  location-icon.png  phone-icon.png  twitter-icon.png  warning-icon.png  youtube-icon.png

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images/icons (hotfix-cleanup)
$ cd ..

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets/images (hotfix-cleanup)
$ cd ..

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3/assets (hotfix-cleanup)
$ cd ..

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$ touch AUDIT_REPORT.md

Baja Malik@LAPTOP-0U4VI34R MINGW64 ~/OneDrive/Documents/evaluasi_pekan_3_grup3 (hotfix-cleanup)
$
    