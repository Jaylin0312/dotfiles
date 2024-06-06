###############################
#  Taps                       #
###############################
tap "1password/tap"
tap "hashicorp/tap"
tap "homebrew/aliases"
tap "homebrew/autoupdate"
tap "homebrew/bundle"
tap "homebrew/cask"
tap "homebrew/cask-drivers"
tap "homebrew/cask-fonts"
tap "homebrew/cask-versions"
tap "homebrew/core"
tap "homebrew/services"
tap "ngrok/ngrok"
tap "pulumi/tap"

###############################
#  Binaries                   #
###############################

# Perhaps most importantly...
brew "zsh" unless OS.linux?

# Better bash as a backup
brew "bash" unless OS.linux?

# GNU utilities (those that come with macOS are outdated)
brew "coreutils"
brew "findutils"
brew "gnu-indent"
brew "gnu-sed"
brew "gnu-tar"
brew "gnu-which"
brew "gnupg"
brew "gnutls"
brew "grep"
brew "make"
brew "moreutils"

# More recent versions of some macOS tools
brew "curl", link: true
brew "gcc"
brew "gmp"
brew "nano"
brew "openssh"
brew "screen"
brew "unzip", link: true
brew "vim"  #, args: ["with-override-system-vi"]

# Other useful binaries
brew "ack"
brew "autoconf"
brew "automake"
brew "ffmpeg"  #, args: ["with-libvpx"]
brew "imagemagick"  #, args: ["with-webp"]
brew "jemalloc"
brew "less"
brew "libsass", args: ["HEAD"]
brew "libyaml"
brew "mtr"
brew "openssl@1.1" if OS.mac?
brew "p7zip"
brew "pkg-config"
brew "readline"
brew "sidneys/homebrew/unrar" if OS.mac?
brew "ssh-copy-id", link: true
brew "tmux"
brew "tree"
brew "wget"  #, args: ["with-iri"]

# Git
brew "git"
brew "git-lfs"
brew "gh"

# Mostly ordinary binaries
brew "asciinema"
brew "ansible"
brew "aws-shell"
brew "awscli"
brew "carthage"
brew "cocoapods"
brew "composer"
brew "doctl"
brew "fx"
brew "go"
brew "guetzli"
brew "hashicorp/tap/packer"
brew "hashicorp/tap/terraform"
brew "hashicorp/tap/vault"
brew "htop"
brew "httpie"
brew "httrack"
brew "hugo", args: ["HEAD"]
brew "ipinfo-cli"
brew "iproute2mac"
brew "jq"
brew "mariadb"
brew "mas" if OS.mac?
brew "mhash"
brew "mkcert"
brew "mysql-client"
brew "ncurses"
brew "neofetch"
brew "netcat"
brew "openjdk"
brew "openvpn"
brew "optipng"
brew "pandoc"
brew "php"
brew "planetscale/tap/pscale"
brew "pngcrush"
brew "postgresql"
brew "protobuf"
brew "pyenv" unless OS.linux?
brew "qemu"
brew "rbenv" unless OS.linux?
brew "rclone"
brew "rlwrap"
brew "ruby-build" unless OS.linux?
brew "rust"
brew "s3cmd"
brew "sass/sass/dart-sass-embedded"
brew "sass/sass/sass"
brew "serverless"
brew "shellcheck"
brew "shfmt"
brew "sqlite"
brew "subversion"
brew "svn"
brew "tor"
brew "torsocks"
brew "volta" unless OS.linux?
brew "whois", link: true

###############################
#  macOS Apps via Cask        #
###############################

cask_args appdir: "/Applications"

# Passwords, VPNs, other Security
cask "1password"
cask "1password-cli"

# Development/Work
cask "eclipse-java"
cask "dbeaver-community"
cask "figma"
cask "microsoft-office"
cask "ngrok/ngrok/ngrok"
cask "postman"
cask "visual-studio-code"

# Virtual Machines (& Docker)
cask "docker"

# Communication/Social
cask "discord"
cask "slack"
cask "zoom"
cask "telegram"

###############################
#  Drivers                    #
###############################

cask "homebrew/cask-drivers/hp-easy-start"
cask "homebrew/cask-drivers/logitech-camera-settings"
cask "homebrew/cask-drivers/logi-options-plus"
cask "homebrew/cask-drivers/logitech-unifying"
cask "homebrew/cask-drivers/razer-synapse"
cask "homebrew/cask-drivers/sonos"

###############################
#  Fonts                      #
###############################

# Monospace
cask "homebrew/cask-fonts/font-cascadia-code"
cask "homebrew/cask-fonts/font-hack"
cask "homebrew/cask-fonts/font-ibm-plex-mono"
cask "homebrew/cask-fonts/font-roboto-mono"
cask "homebrew/cask-fonts/font-sf-mono"
cask "homebrew/cask-fonts/font-sf-mono-for-powerline"
cask "homebrew/cask-fonts/font-source-code-pro"

# Sans/Serif
cask "homebrew/cask-fonts/font-comic-neue"
cask "homebrew/cask-fonts/font-inter"
cask "homebrew/cask-fonts/font-open-sans"
cask "homebrew/cask-fonts/font-roboto"
cask "homebrew/cask-fonts/font-sf-compact"
cask "homebrew/cask-fonts/font-sf-pro"