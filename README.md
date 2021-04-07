# share

Share files from your computer.

## Usage

```
usage: share [-p Port] [files...]
```

Press Enter to quit the program.

When the ip-address with the port appears, people can download the shared files.

## Install

### For Linux

```
git clone https://github.com/nmke-de/share
sudo cp share/share /usr/bin/share
```

### For MacOSX

Open Share.pkg and follow the install instructions.

### Dependencies

NodeJS should be installed in order for share to work. On MacOSX Big Sur or higher, [this](https://www.python.org/downloads/mac-osx/) version of Python needs also be installed. If you want to use `take`, you will have to make sure that `wget` is installed as well.
