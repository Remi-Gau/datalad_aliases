# Oh-my-zsh datalad aliases plugin

This plugin provides some [oh-my-zsh](https://ohmyz.sh/) [aliases](#aliases) for
a few useful [datalad](http://handbook.datalad.org/en/latest/index.html#)
commands.

# Installation

See [here](./datalad/README.md#installation)

## Aliases

| Alias    | Command                                |
| :------- | :------------------------------------- |
| ddiff    | dalalad diff                           |
| dcl      | datalad clone                          |
| dcona    | datalad containers-add                 |
| dconl    | datalad containers-list                |
| dconr    | datalad containers-remove              |
| dconru   | datalad containers-run                 |
| dcr      | datalad create                         |
| dcrf     | datalad create --force                 |
| dcrfbids | datalad create --force -c bids         |
| dcrftext | datalad create --force -c text2git     |
| dcrfyoda | datalad create --force -c yoda         |
| dg       | datalad get                            |
| dgr      | datalad get -r                         |
| di       | datalad install                        |
| diget    | datalad install --get-data             |
| direc    | datalad install --recursive            |
| digetrec | datalad install --get-data --recursive |
| ds       | datalad save                           |
| dsm      | datalad save --message                 |
| dsr      | datalad save --recursive               |
| dsru     | datalad save --recursive -u            |
| dsu      | datalad save -u                        |
| dls      | datalad ls                             |
| dp       | datalad push                           |
| dpr      | datalad push -r                        |
| dprt     | datalad push -r --to                   |
| dpt      | datalad push --to                      |
| dr       | datalad run                            |
| drp      | datalad run-procedure                  |
| drpd     | datalad run-procedure --discover       |
| drpbids  | datalad run-procedure cfg_bids         |
| drptext  | datalad run-procedure cfg_text2git     |
| drpyoda  | datalad run-procedure cfg_yoda         |
| dsib     | datalad siblings                       |
| dsiba    | datalad siblings add                   |
| dsibc    | datalad siblings configure             |
| dsibr    | datalad siblings remove                |
| dsub     | datalad subdatasets                    |
| dst      | datalad status                         |
| dul      | datalad unlock                         |
| dulr     | datalad unlock --recursive             |
| dup      | datalad update                         |
| dupm     | datalad update --merge                 |
