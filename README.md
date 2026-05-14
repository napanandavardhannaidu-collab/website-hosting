1  sudo apt-get update
    2  sudo apt-get upgrade -y
    3  sudo apt-get install nginx
    4  sudo systemctl start nginx
    5  sudo systemctl status nginx
    6  cd /
    7  ls
    8  cd /var/www/html
    9  ls
   10  sudo vi index.nginx-debian.html 
   11  sudo vi index.html
   12  ls
   13  wget https://templatemo.com/download/templatemo_621_luminary 
   14  sudo apt-get install unzip
   15  ls
   16  cd 
   17  ls
   18  wget https://templatemo.com/download/templatemo_621_luminary 
   19  ls
   20  sudo apt-get install unzip
   21  sudo mv templatemo_621_luminary templatemo_621_luminary.zip
   22  ls
   23  sudo unzip templatemo_621_luminary.zip 
   24  ls
   25  cd templatemo_621_luminary/
   26  ls
   27  sudo cat index.html 
   28  ls
   29  sudo cat images
   30  cd
   31  ls
   32  cd /var/www/html
   33  ls
   34  sudo rm index.html
   35  ls
   36  cd 
   37  ls
   38  cd templatemo_621_luminary/
   39  ls
   40  sudo mv * /var/www/html
   41  ls
   42  cd
   43  ls
   44  cd /var/www/html
   45  ls
   46  sudo git init
   47  sudo git add .
   48  ls
   49  cd templatemo-621-luminary-script.js
   50  cd ~/templatemo_621_luminary 
   51  ls
   52  cd
   53  cd /var/www/html
   54  ls
   55  sudo git init
   56  sudo git add .
   57  git commit -m "Added static website project" 
   58  git config --global user.name "N.Nanda vardhan naidu"
   59  git config --global user.email "napanandavardhannaidu@gmail.com"
   60  git commit -m "Added static website project" 
   61  git config --global --add safe.directory /var/www/html 
   62  git commit -m "Added static website project" 
   63  sudo git config --global --add safe.directory /var/www/html 
   64  sudo git commit -m "Added static website project"  
   65  sudo git config --global user.email "napanandavardhannaidu@gmail.com"
   66  sudo git config --global user.name "N.Nanda vardhan naidu"
   67  sudo git commit -m "Added static website project"   
   68  sudo git branch -M main
   69  sudo git remote add origin https://github.com/napanandavardhannaidu-collab/website-hosting.git 
   70  sudo git push -u origin main 
   71  cd
   72  history
