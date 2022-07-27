# Solana-Token-Gating---Moralis

This is a plain vanilla Js script for token gating content on Solana via Moralis API. 

You will need a moralis account. 

1. Copy the script into your head code for unkpg moralis and web3.

2. Copy the body script into your body page and replace 2 sections.

3. Rename the div with a class id matching whatever you put in this section "whatever the page wrapper for your site is called by id"

A) Your Server URL & App ID which can be obtained by creating a Moralis Dapp. They currently do not show a ui option, just select all networks and create as basic server. 
You will need to place thos where you see "yoururl" & "yourid"

B)The section that says "Symbol/Collection you want to gate ex DUCKS" needs to be replaced with the symbol for the nft collection you're wanting to gate. If you're not familiar
with how to do this, you can simply navigate to any solscan link for an nft you own, and then click the metadata tab near the middle of the page. That will display the 
metadata info, and it will list your symbol as "Symbol". Just plug that in and publish your page. 

Once this is working it will authenticate via Phantom on every page the code is included on, and it will check for the NFT symbol to be present before reavealing the div 
you titled the class id for above.

If this script helped you out, please consider joining the Ducks Dao on solana or tossing ya boi some solana sheckles. 

BayrxPkpURe5hEM2PGta1g2oTAMM3uUp2GseYsrtLrW3

-Kichen
