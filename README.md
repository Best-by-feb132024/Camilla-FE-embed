# Camilla-FE-embed
NSFW textual inversion embed for stable diffusion based on R34 images of Camilla from fire emblem. To be used with stable diffusion (prefferably waifu diffusion 1.3 or Novel AI)

![](https://static.wikia.nocookie.net/feheroes_gamepedia_en/images/e/ec/Camilla_Bewitching_Beauty_Face.webp/revision/latest?cb=20190920200248)

# Installing and using with AUTOMATIC1111's SD webui
To install simply download the `Camilla-FE.bin` file and place it in your `stable-diffusion-webui-master\embeddings` folder. Then in order to use the embedding enter in the filename `Camilla-FE.bin` or the token `<Camilla-FE>` in the prompt field. (You can download SD webui [here](https://github.com/AUTOMATIC1111/stable-diffusion-webui) )



# Model details

15-16 512x512 pixel images were used to train the textual inversion embed.

* 2D anime/cartoon/digital art style
* front facing view (1 or 2 were from the side)
* contained camilla's face, purple hair, and breasts

This was trained with the google collab for textual inversion and **not** the webui version. This means I couldn't add tags. If you'd like to retrain the model with appropriate tags on the inputs you have my blessing (but please share the final result).

## Comparisson

With `Camilla-FE.bin`:

![]()

* prompt: A curvy Camilla-FE.bin with purple hair wearing a bikini. thick thighs, hourglass figure, (abs). solo.
* Negative prompt: ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), (((more than 2 nipples))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), obese, overweight, pregnant, plump, male focus, genderswap, furry, 1boy, bald, fat, uneven sized eyes,
* Steps: 44, Sampler: Euler a, CFG scale: 10, Seed: 78253082, Face restoration: CodeFormer, Size: 512x512, Model hash: 925997e9


Using `Camilla-FE.bin` at the end:

![]()

* Prompt: A curvy woman with purple hair wearing a bikini. thick thighs, hourglass figure, (abs). ((Camilla-FE.bin)), solo.
* Negative prompt: ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), (((more than 2 nipples))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), obese, overweight, pregnant, plump, male focus, genderswap, furry, 1boy, bald, fat, uneven sized eyes,
* Steps: 44, Sampler: Euler a, CFG scale: 10, Seed: 78253082, Face restoration: CodeFormer, Size: 512x512, Model hash: 925997e9


Without:

![]()

* Prompt: A curvy woman with purple hair wearing a bikini. thick thighs, hourglass figure, (abs). solo.
* Negative prompt: ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), (((more than 2 nipples))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), obese, overweight, pregnant, plump, male focus, genderswap, furry, 1boy, bald, fat, uneven sized eyes,
* Steps: 44, Sampler: Euler a, CFG scale: 10, Seed: 78253082, Face restoration: CodeFormer, Size: 512x512, Model hash: 925997e9

# Why?

I am incredibly horny for Camilla.
