# Camilla-FE-embed
NSFW textual inversion embed for stable diffusion based on R34 images of Camilla from fire emblem. To be used with stable diffusion (prefferably waifu diffusion 1.3 or Novel AI)

![](https://static.wikia.nocookie.net/feheroes_gamepedia_en/images/e/ec/Camilla_Bewitching_Beauty_Face.webp/revision/latest?cb=20190920200248)

# Installing and using with AUTOMATIC1111's SD webui
To install simply download the `Camilla-FE.bin` file and place it in your `stable-diffusion-webui-master\embeddings` folder. Then in order to use the embedding enter in the filename `Camilla-FE.bin` or the token `<Camilla-FE>` in the prompt field. (You can download SD webui [here](https://github.com/AUTOMATIC1111/stable-diffusion-webui) )



# Model details (V2)

24 512x512 pixel images were used to train the textual inversion embed.

* 2D anime/cartoon/digital art style
* front facing view (1 or 2 were from the side)
* contained camilla's face, purple hair, and breasts
* file names had basic tags incase the google collab can understand those.

This was trained with the google collab for textual inversion and **not** the webui version. This means there's a chance it didn't take any tag inputs from file names. If you'd like to retrain the model with appropriate tags on the inputs I can share the original training images (but please share the final result). Thankfully it does produce noticable changes in outputs, with outputs having Camilla's signature long purple hair and big-huge breasts.

## Comparissons

With `Camilla-FE.bin`:

![](https://github.com/Best-by-feb132024/Camilla-FE-embed/blob/main/example%20outputs/beach%20ghibli%20v2%20with%20camilla.png)

* prompt: a Camilla-FE.bin wearing a bikini at the beach, by Studio Ghibli. (large breasts), ((hair over one eye)), long hair, curvy, thick thighs, upper body, wide hips, (purple hair), best quality, detailed face, character focus, [masterpiece], absurd res, detailed eyes, sexy face, [intricate details], [[photorealistic]], detailed facial features, dynamic lighting, sharp focus
* Negative prompt: ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), (((more than 2 nipples))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), obese, overweight, pregnant, plump, male focus, genderswap, furry, bald, fat, prosthesis, prosthetic, artificial limb, crossed eyes, lowres, worst quality, low quality, jpeg artifacts, loli, 1boy, shota, asymmetrical breasts, ((tiny breasts)), ((small breasts))
* Steps: 64, Sampler: Euler a, CFG scale: 10, Seed: 1688581248, Face restoration: GFPGAN, Size: 512x512, Model hash: 925997e9, Model: final-pruned


Using Camilla instead of the embed:

![](https://github.com/Best-by-feb132024/Camilla-FE-embed/blob/main/example%20outputs/beach%20ghibli%20no%20embed.png)

* Prompt: Camilla wearing a bikini at the beach, by Studio Ghibli. (large breasts), ((hair over one eye)), long hair, curvy, thick thighs, upper body, wide hips, (purple hair), best quality, detailed face, character focus, [masterpiece], absurd res, detailed eyes, sexy face, [intricate details], [[photorealistic]], detailed facial features, dynamic lighting, sharp focus
* Negative prompt: ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), (((more than 2 nipples))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), obese, overweight, pregnant, plump, male focus, genderswap, furry, bald, fat, prosthesis, prosthetic, artificial limb, crossed eyes, lowres, worst quality, low quality, jpeg artifacts, loli, 1boy, shota, asymmetrical breasts, ((tiny breasts)), ((small breasts))
* Steps: 64, Sampler: Euler a, CFG scale: 10, Seed: 1688581248, Face restoration: GFPGAN, Size: 512x512, Model hash: 925997e9, Model: final-pruned


Without:

![](https://github.com/Best-by-feb132024/Camilla-FE-embed/blob/main/example%20outputs/beach%20ghibli%20woman%20prompt.png)

* Prompt: a woman wearing a bikini at the beach, by Studio Ghibli. (large breasts), ((hair over one eye)), long hair, curvy, thick thighs, upper body, wide hips, (purple hair), best quality, detailed face, character focus, [masterpiece], absurd res, detailed eyes, sexy face, [intricate details], [[photorealistic]], detailed facial features, dynamic lighting, sharp focus
* Negative prompt: ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), (((more than 2 nipples))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), obese, overweight, pregnant, plump, male focus, genderswap, furry, bald, fat, prosthesis, prosthetic, artificial limb, crossed eyes, lowres, worst quality, low quality, jpeg artifacts, loli, 1boy, shota, asymmetrical breasts, ((tiny breasts)), ((small breasts))
* Steps: 64, Sampler: Euler a, CFG scale: 10, Seed: 1688581248, Face restoration: GFPGAN, Size: 512x512, Model hash: 925997e9, Model: final-pruned


## Version comparissons 

![](https://github.com/Best-by-feb132024/Camilla-FE-embed/blob/main/example%20outputs/v1%20vs%20v2.png)

* Prompt: a Camilla-FE.bin wearing a bikini at the beach, by Studio Ghibli. (large breasts), ((hair over one eye)), long hair, curvy, thick thighs, upper body, wide hips, (purple hair), best quality, detailed face, character focus, [masterpiece], absurd res, detailed eyes, sexy face, [intricate details], [[photorealistic]], detailed facial features, dynamic lighting, sharp focus
* Negative prompt: ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), (((more than 2 nipples))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), obese, overweight, pregnant, plump, male focus, genderswap, furry, bald, fat, prosthesis, prosthetic, artificial limb, crossed eyes, lowres, worst quality, low quality, jpeg artifacts, loli, 1boy, shota, asymmetrical breasts, ((tiny breasts)), ((small breasts))
* Steps: 64, Sampler: Euler a, CFG scale: 10, Seed: 1236903230, Face restoration: GFPGAN, Size: 512x512, Model hash: 925997e9, Model: final-pruned



# Prompt tips

The following prompt additions I've noticed help, they are basically all hallmark traits of Camilla you are emphasizing to the AI

* hair over one eye / (hair over one eye)
  * BY FAR THE MOST HANDY / IMPORTANT ONE. In general stable diffusion struggles with consistent eyes, and given Camilla always has hair covering 1 of her eyes I've found not including this vs including this has night and day differences.
* purple hair
* long hair
* purple eyes
* curvy 
  * not as required to make output look like camilla entirely, but she is curvy in basically all art and this still helps
* [looking at viewer]
  * all the input data has her looking at you, or looking at a 3/4 angle to the side. So it is handy


## Hair covering 1 eye vs both eyes shown comparisson 

*Results shown were done using the V1 model and not V2*

Here is when the output doesn't cover 1 eye with purple hair:

![](https://github.com/Best-by-feb132024/Camilla-FE-embed/blob/main/example%20outputs/When%20the%20hair%20over%20eye%20tag%20misses.png)

and here is when the prompt for hair over one eye works:

![](https://github.com/Best-by-feb132024/Camilla-FE-embed/blob/main/example%20outputs/when%20the%20hair%20over%20eye%20hits.png)


Note: both used the same prompt (save for the hair not covering eyes one not emphasizing `hair over one eye` with paranthesis `(hair over one eye)`

<Camilla-fe>, abs, curvy, (hair over one eye), arms behind back,
best quality, [purple hair], [long hair], [photorealistic], [[feminine]], (in heat:0.12), [solo], [cowboy shot], [[beach]], (detailed face:1) (detailed eyes:1), [[absurd res]], [nsfw], [[[[intricate details]]]], highly detailed, smooth, sharp focus
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, obese, fat, pregnant, bald, fat, prosthesis, prosthetic, artificial limb, 1boy, [male focus], anorexic, mutated hands, (fused fingers), (too many fingers), (((long neck))), ((extra heades)), different pupils
Steps: 84, Sampler: Euler a, CFG scale: 8, Seed: 2903797192, Face restoration: CodeFormer, Size: 512x512, Model hash: 925997e9, Variation seed: 910849907, Variation seed strength: 0.32

Used embeddings: Camilla-FE [e687]


# Why?

I am incredibly horny for Camilla.
