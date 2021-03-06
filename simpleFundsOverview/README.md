# Funds overview plugin

This plugin extends the c-lightning command line API with the `funds` command.
Users can get a quick overview of their total funds, the offchain funds in
channels and the onchain funds in unspent transaction outputs. 

run the plugin with:

```
lightningd --plugin=/path/to/c-lightning-plugin-collection/simpleFundsOverview/funds.py
```

Once the plugin is active you can run `lightning-cli help funds`
to learn about the command line API.

The easiest call will be `lightning-cli funds` without any additional arguments. 

you can create the plugin yourself by extending `fundslapp.py` following this
video: https://youtu.be/FYs1I-pCJIg

## About the plugin
This plugin was created and is maintained by Rene Pickhardt. It shall serve as
an educational resource on his Youtube channel at:

https://www.youtube.com/user/RenePickhardt

The plugin is licensed like the rest of c-lightning with BSD-MIT license
and comes without any warrenty (see LICENSE file)

If you like my work feel free to support me on patreon:
https://www.patreon.com/renepickhardt

Or support the crowdfunding campaign of my book project about the lightning network at:
https://tallyco.in/s/lnbook/

or leave me a tip on my donation page (comming from the donation plugin):
https://ln.rene-pickhardt.de/

The work was partially sponsored by http://fulmo.org/
