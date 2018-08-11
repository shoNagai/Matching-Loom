# Matching-Loom

## What is this dapps?
Matching Loom is dapps like a Tinder App.

- All swiped data will be saved on Dapp Chain.
- You can see the tastes of matching partners. (transparent)
- It works on the side chain of Loom.
  - If you try to return token you got using fake photos back to the main chain, it will be challenged…….Not implemented🙇

## Why made?
- Because of SNS using Dapp Chain(DPos is fast), we wanted to record Instant emotions.
- We thought that it would be incentive to be swiped nice.

# How to use

## start loom chain
```command:install loom & start
wget https://storage.googleapis.com/private.delegatecall.com/loom/osx/build-285/loom
chmod +x loom
./loom init
./loom run
```

## contract Development
```command:createkey & deploy contract to loom chain 
loom genkey -a public_key -k private_key
truffle deploy --network loom_dapp_chain
```

## start
```command:start app
npm install
npm start
```

## Team member
https://github.com/studioTeaTwo さん！

『DApps SNS Hackathon by Loom Network×GameWith』
https://neutrino.connpass.com/event/94434/
