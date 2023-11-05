## Readme for developers (-: me)

### Pulling new DM42 release (example)

git switch master
git fetch upstream
git merge upstream/master

git checkout -b pcm-3.20.x
git merge pcm-3.19.x


### Release process (example)

#### For DM42free42 and DM42PGM

1. git push --set-upstream origin pcm-3.21.x
2. git tag -a DM42pcm-3.21.8 -m "Releasing DM42pcm v3.21.8"
3. git push origin DM42pcm-3.21.8

#### For DM42pcm

1. git push

#### Create DMCP + DM42 combo

Use mkcombo script from DM42PGM

See https://github.com/swissmicros/DMCP_SDK/blob/master/keymap_utils/README.md)


### Development environment setup

sudo apt install gcc-arm-none-eabi

sudo snap install --classic code
