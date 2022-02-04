# AWS Dual Crypto Coin Miner

AWS CloudFormation Template for Dual Miner (GPU + CPU) for Ethereum and other ALT coins (Monero or Shiba Inu)

# Implementation (3 mins)

Here is quick way to start Dual coin mining on AWS in under 3 minutes. This template is based on Michael Ludwig's repo (in acknowledgements below)
Read about the profitability on AWS mining in his article [Mining Ethereum on AWS - is it worth it?](https://michael-ludvig.medium.com/mining-ethereum-on-aws-is-it-worth-it-f13645c12eec)

1. Login to your AWS account and have your Ethereum and other ALT coin (Monero or Shiba Inu) wallet address ready

2. Launch the [stack](https://github.com/awsdataarchitect/aws-eth-xmr-shib-dual-miner/blob/main/miner.yaml) in one or more of the cheapest regions. Sometimes spot capacity is not available in a particular region, in that case try a different one.

3. Note the template uses Monero (but you can simply replace the XMR mining pool with Shiba Inu if you want to try out SHIB mining using CPU)

Just be aware that it’s still not worth it unless you get a SPOT instance rate of < $0.12/hr on the g4ad.xlarge instance. This is the best instance that I have tried so far and was somewhat profitable in Jan 2022.

## Acknowledgements
 
 - [Original CloudFormation Template](https://github.com/mludvig/aws-ethereum-miner)



## Support

Did you find this template useful ? Any ETH amount sent to my address will be much appreciated: 0xBE0eACFA90d800A2504a9aDB4249DCa435C7F579
