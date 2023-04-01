# Stable-Diffusion-API-NodeJS-AI-ImageGenerator
An API NodeJS script to automate image generation using Stable Diffusion AI Image Generator


##
<h3>Subscribe to my Youtube! Net2Dev</h3>
<a href="http://youtube.net2dev.io" target="_blank"><img src="https://github.com/net2devcrypto/misc/blob/main/ytlogo2.png" width="150" height="40"></a>

<img src="https://raw.githubusercontent.com/net2devcrypto/misc/main/stablediffusion.png" width="350" height="60">


** THE FILES ATTACHED TO THIS REPO ARE FOR EDUCATIONAL PURPOSES ONLY **
** USE IT AT YOUR OWN RISK** **I'M NOT RESPONSIBLE FOR ANY USE, ISSUES ETC.. **


## Step 1

Download stablediffusionapi folder from this repo.

## Step 2

Extract and navigate to project folder then install dependencies: npm i

```shell
cd stablediffusionapi
npm i
```
## Step 3

Create your Account in Stablediffusion: https://stablediffusionapi.com/

## Step 4

Create API key then copy it.
Update stablegenerate.js and add your api key:

```shell
const apiKey = 'REPLACE-WITH-YOUR-API-KEY';
```

## Step 4

Add your prompt description of what you want to generate.

```shell
const prompt = 'a dog walking on the beach with sunglasses, portrait, ultra realistic, futuristic background , concept art, intricate details, highly detailed';
```

## Step 5

Add how many pics you want to generate:

```shell
const numberOfPics = '3'
```

## Step 6
- Save and execute in your terminal:

```shell
node stablegenerate.js
```

Pictures will be inside the "pics" folder once generated.

Follow me in Youtube @Net2Dev!!
