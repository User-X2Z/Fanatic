# Fanatic
Support your coin with Fanatic.

![백서 이미지 (1)](https://user-images.githubusercontent.com/98400439/152129611-40600c27-a294-4f1b-9980-7de9170d22dc.png)

## PFP

We make 10000 PFPs with different combinations of faces and emoticons.

The number of 10000 is mathematically designed using the concept of combination.

Here are the detailed information about how we make Fanatic:

* 100_face.txt: basic faces of fanatic which are Top 100 market cap coins.


* 100_emoticon.txt: emoticons with 100 combinations of Top, Mid, Bot elements.

  All emoticons are composed of Top, Mid, Bot and there are 5 choices for each position as following:

  Top - (none, headband, headset, fedora, crown)
  
  Mid - (none, eyes, round_glasses, pixel_sunglasses, pirate_eyepatch)
  
  Bot - (none, mouth, mustache, beard, blusher)

  The color of all elements are same with black. Then the number of cases is 5 x 5 x 5 = 125. 
  
  And we will not handle none case for Mid, which means there will be at least one element in the Mid position. 
  
  Then, 25 cases with none mid are excluded from total number. Thus, the 100 different combination is calculated by following:

  Total cases - none Mid cases = 125 - 25 = 100.


* 10000_fanatic.txt

  All combinations of 100 faces and 100 emoticons finally make 10000 different Fanatic.

  In this setting, since all faces and emoticons are equally distributed, the probability for each component is equal in statistics.

  With this calculation, we will not specify any information about the rarity score of each combination. 
  
  However, we expect the rarity can be naturally determined by users’ preference or demand on different combinations.


## Minting

We randomly split 10000 fanatics with airdrop and 10 rounds with numpy random seed.

We don't own any pre-order supply for our team, so 100% supply will be released through airdrop and minting rounds.

In each csv file, the combinations for sale on specific event are already determined.

Total 10000 supplies are listed as following: 

* Airdrop_list.csv (100)

* Round(1-10)_list.csv (1000, 1000, 1000, 1000, 1000, 1000, 1000, 1000, 1000, 900)

On every minting rounds, the additional listings according to our holders' vote result will be announced and added later.

For detailed information about Fanatic, please read our whitepaper .
