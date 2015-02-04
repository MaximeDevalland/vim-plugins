# vim-plugins

# Installation
### ~/.vimrc
    filetype plugin on
    filetype indent on
    autocmd BufWritePre /etc/bind/zones/ Soa

### Copy Soa.vim in ~/.vim/plugin

# Usage
(Your zone file must match this format YYYYMMDD## ; serial)

Open a zone file and type in 

    :Soa
