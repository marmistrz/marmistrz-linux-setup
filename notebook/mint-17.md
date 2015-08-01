Also applies to: Ubuntu Trusty

Install the system with separate /home and /

Install a newer kernel if you need it.

Core stuff now: TLP and Bumblebee. First make sure that you have the headers for your kernel!

    add-apt-repository -y ppa:linrunner/tlp
    apt-get update
    apt-get install tlp tlp-rdw bumblebee bumblebee-nvidia primus nvidia-346

On Ubuntu use other drivers instead (which?)

Set up Thunderbird with addons: Auto Save Draft Folders, Firetray

Now secondary apps:
    add-apt-repository -y ppa:tsbarnes/indicator-keylock 
    apt-get update
    apt-get install git imagemagick indicator-keylock mnemosyne redshift-gtk wine wine-gecko2.21

Add Redshift and indicator-keylock to autostart // TODO: Mint indicator-* workaround

Install RAVE-X and set it up (maybe automatically would be feasible?)

    add-apt-repository -y ppa:ravefinity-project/ppa
    apt-get update
    apt-get install rave-x-colors-icons

Install bumblebee-ui.
Override the date format in lockscreen (FIXME: to what?)

Copy the config files (setting brightness on boot)

    cp -av conf/* /
