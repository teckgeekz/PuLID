# PuLID v1.1

✅ Release PuLID v1.1 for SDXL models. In this version, we have made the following improvements:
- **stronger ID editability and prompt-following ability**. As shown in the examples below, pulid v1.1 can edit style, viewpoint, expression, lighting, etc., while maintaining a high degree of ID similarity.
- **better compatibility with community models**. According to our tests, PuLID-v1.1 performs well on some popular and powerful base models in the community, such as Juggernaut-XL, RealVisXL, and DreamShaper-XL-Lightning.
- **better naturalness**. We have noted that without any tricks, the faces generated by PuLID-v1 can be somewhat blurry and lack detail. The v1.1 version, when combined with more powerful base models, has shown improvements in facial clarity and naturalness.
- ID similarity has beed slightly improved.

Note: The v1.1 model does not perform as well as v1 on the SDXL-lightning-4step base model, so if you want to use SDXL-lightning-4step as the base model, we still recommend using the v1 model.


Following are some examples generated by PuLID-v1.1, you can reproduce these results from our Gradio demo.
![release_v1 1](https://github.com/user-attachments/assets/3b24e9b2-59c0-4bfb-8658-a26e730c298d)

## How to use

### Local Gradio demo
```bash
python app_v1.1.py --base BASE_MODEL
Usage:
  -base: can be RunDiffusion/Juggernaut-XL-v9 or Lykon/dreamshaper-xl-lightning
         for each supported base model, we prepare some examples in the bottom of the gradio demo, please try these examples first.
```

### Online demo
We plan to upgrade the [PuLID HF demo](https://huggingface.co/spaces/yanze/PuLID) to v1.1 soon, please stay tuned.

