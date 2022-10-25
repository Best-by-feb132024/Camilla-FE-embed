# Info on the old V1 model

The first embed model created for this.

# Model details

15-16 512x512 pixel images were used to train the textual inversion embed.

* 2D anime/cartoon/digital art style
* front facing view (1 or 2 were from the side)
* contained camilla's face, purple hair, and breasts

This was trained with the google collab for textual inversion and **not** the webui version. This means I couldn't add tags. If you'd like to retrain the model with appropriate tags on the inputs I can share the original training images (but please share the final result). Thankfully it does produce noticable changes in outputs, with outputs having Camilla's signature long purple hair and big-huge breasts.

## Comparissons

With `Camilla-FE.bin`:

![](https://github.com/Best-by-feb132024/Camilla-FE-embed/blob/main/example%20outputs/with%20camilla.png)

* prompt: A curvy Camilla-FE.bin with purple hair wearing a bikini. thick thighs, hourglass figure, (abs). solo.
* Negative prompt: ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), (((more than 2 nipples))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), obese, overweight, pregnant, plump, male focus, genderswap, furry, 1boy, bald, fat, uneven sized eyes,
* Steps: 44, Sampler: Euler a, CFG scale: 10, Seed: 78253082, Face restoration: CodeFormer, Size: 512x512, Model hash: 925997e9


Using `Camilla-FE.bin` at the end:

![](https://github.com/Best-by-feb132024/Camilla-FE-embed/blob/main/example%20outputs/with%20camilla%20as%20add%20on.png)

* Prompt: A curvy woman with purple hair wearing a bikini. thick thighs, hourglass figure, (abs). ((Camilla-FE.bin)), solo.
* Negative prompt: ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), (((more than 2 nipples))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), obese, overweight, pregnant, plump, male focus, genderswap, furry, 1boy, bald, fat, uneven sized eyes,
* Steps: 44, Sampler: Euler a, CFG scale: 10, Seed: 78253082, Face restoration: CodeFormer, Size: 512x512, Model hash: 925997e9


Without:

![](https://github.com/Best-by-feb132024/Camilla-FE-embed/blob/main/example%20outputs/without%20camilla.png)

* Prompt: A curvy woman with purple hair wearing a bikini. thick thighs, hourglass figure, (abs). solo.
* Negative prompt: ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), (((more than 2 nipples))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck))), obese, overweight, pregnant, plump, male focus, genderswap, furry, 1boy, bald, fat, uneven sized eyes,
* Steps: 44, Sampler: Euler a, CFG scale: 10, Seed: 78253082, Face restoration: CodeFormer, Size: 512x512, Model hash: 925997e9
