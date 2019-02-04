# Local Setup
## Windows
1. Download [git] (https://git-scm.com/download/win)
2. Download [vim] (https://www.vim.org/download.php#pc)
.. Add to PATH
3. Create SSH key pair
.. ssh-keygen -t rsa -b 4096 -C "christinaleuci@gmail.com"
.. start SSH agent ssh-agent -s
.. If it doesn't run check in local services and set to automatically start
.. Add to SSH and Github ssh-add ~/.ssh/id_rsa
