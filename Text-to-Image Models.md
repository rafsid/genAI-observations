# Table
## Text-To-Image Models
### Source: Various (used SearchGPT)
### As on : 18-Aug-2024

|Model Name|Country|Company/Organization|Billions of Parameters|Open Source|ELO Rating|ComfyUI Compatible|Adapter Support|Training Data|Model Type|Resolution|Inference Time|Cost (per 1,000 images)|API Availability|URL|
|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|
|Midjourney v6|USA|Midjourney|Undisclosed|Closed Source|1,176|No|No|Proprietary|Transformer|1024x1024|~5-10s|N/A (subscription model)|No|Midjourney|
|DALL·E 3 HD|USA|OpenAI|Undisclosed (~B scale)|Closed Source|1,110|No|No|Proprietary|Transformer|1024x1024|~10s|~$10 per 1,000 images|Yes|DALL·E|
|Stable Diffusion 2|UK|Stability AI|1.5T images, ~B params|Open Source|Not Available|Yes|Yes (LoRA)|LAION|Latent Diffusion Model|512x512|~5s|Free (Open Source)|Yes|Stable Diffusion|
|Stable Diffusion 3|UK|Stability AI|Not Publicly Disclosed|Open Source|1,156|Yes|Yes (LoRA, ControlNet)|LAION|Latent Diffusion Model|1024x1024|~5s|Free (Open Source)|Yes|Stable Diffusion|
|DeepFloyd IF|UK|Stability AI|1B|Open Source|Not Available|Yes|Yes (LoRA)|LAION|Transformer|1024x1024|~7s|Free (Open Source)|Yes|DeepFloyd IF|
|Playground v2.5|Global (Community)|Playground AI|Not Publicly Disclosed|Open Source|1,045|Yes|Yes (LoRA)|Mixed datasets|Transformer|512x512|~5-10s|Free|Yes|Playground AI|
|DreamShaper v7|Global (Community)|CivitAI|Not Publicly Disclosed|Open Source|Not Available|Yes|Yes (LoRA)|Mixed datasets|Latent Diffusion Model|1024x1024|~5s|Free (Open Source)|Yes|CivitAI|
|Dreamlike Photoreal|Global (Community)|DreamlikeArt|Not Publicly Disclosed|Open Source|Not Available|Yes|Yes (LoRA)|Mixed datasets|Latent Diffusion Model|512x512|~5s|Free (Open Source)|Yes|DreamlikeArt|
|Muse|USA|Google Research|Not Publicly Disclosed|Closed Source|Not Available|No|No|Proprietary|Transformer|1024x1024|~10s|Not Publicly Available|No|Muse|
|DreamBooth|USA|Google Research|Not Publicly Disclosed|Open Source|Not Available|Yes|Yes (LoRA)|Proprietary|Latent Diffusion Model|512x512|~5s|Free (Open Source)|Yes|DreamBooth|
|Imagen|USA|Google Research|Not Publicly Disclosed|Closed Source|Not Available|No|No|Proprietary|Diffusion|1024x1024|~8-10s|Not Publicly Available|No|Imagen|
|Make-A-Scene|USA|Meta|Not Publicly Disclosed|Closed Source|Not Available|No|No|Proprietary|Transformer|1024x1024|~10s|Not Publicly Available|No|Make-A-Scene|
|Waifu Diffusion|Global (Community)|Stable Diffusion Fork|Not Publicly Disclosed|Open Source|Not Available|Yes|Yes (LoRA)|LAION|Latent Diffusion Model|512x512|~5s|Free (Open Source)|Yes|Waifu Diffusion|
|FLUX 1.0 (pro)|Germany|Black Forest Labs|Not Publicly Disclosed|Open Source|1,144|Yes|Yes (LoRA)|Mixed datasets|Latent Diffusion Model|1024x1024|~6s|Free (Open Source)|Yes|FLUX 1.0|
|Kandinsky 2.2|USA|University of Chicago|1B|Open Source|Not Available|Yes|Yes (LoRA)|Proprietary|Latent Diffusion Model|1024x1024|~7s|Free (Open Source)|Yes|Kandinsky|
|Rinna|Japan|Microsoft Japan|Not Publicly Disclosed|Closed Source|Not Available|No|No|Proprietary|Transformer|1024x1024|~8-10s|Not Publicly Available|No|Rinna|
|Perchance AI|Sweden|Perchance AI|Not Publicly Disclosed|Open Source|Not Available|Yes|Yes (LoRA)|Mixed datasets|Latent Diffusion Model|1024x1024|~6s|Free (Open Source)|Yes|Perchance AI|

# Table
## Text-To-Image Training Dataset
### Source: Various (used SearchGPT)
### As on : 18-Aug-2024

|Dataset Name|Source/Organization|Description|Size (Images)|Languages|Licensing|Public Availability|Preprocessing Required|Metadata (Text/Image)|Image Resolution|
|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|
|LAION-5B|LAION|Large-scale image-text pairs dataset for training|5 billion|Multilingual|Creative Commons|Public|Yes|Yes (Captions)|Varied (up to 1024x1024)|
|COCO|Microsoft|Common Objects in Context, used for object recognition|330K|English|Public|Public|Yes|Yes (Annotations)|640x480|
|Conceptual Captions|Google Research|High-quality image-caption dataset from web images|3.3 million|English|Free for non-commercial use|Public|Yes|Yes (Captions)|Varied (up to 1024x1024)|
|Open Images V6|Google|Diverse dataset for image classification, object detection, etc.|9 million|Multilingual|Public|Public|Yes|Yes (Annotations)|Varied (up to 1024x1024)|
|Flickr30k|University of Illinois|Image dataset with natural language captions|31K Here's the dataset table that includes columns relevant to an AI researcher working on training their own Text-to-Image model:| | | | | | |
|Dataset Name|Source/Organization|Description|Size (Images)|Languages|Licensing|Public Availability|Preprocessing Required|Metadata (Text/Image)|Image Resolution|
|LAION-5B|LAION|Large-scale dataset of image-text pairs, diverse domains|5 billion|Multilingual|Creative Commons|Public|Yes|Yes (Captions)|Varied (up to 1024x1024)|
|COCO|Microsoft|Common Objects in Context, object detection & segmentation|330K|English|Public|Public|Yes|Yes (Annotations)|640x480|
|Conceptual Captions|Google Research|High-quality web-crawled image-caption pairs|3.3 million|English|Free for non-commercial use|Public|Yes|Yes (Captions)|Varied (up to 1024x1024)|
|Open Images V6|Google|Diverse image dataset with annotations for multiple tasks|9 million|Multilingual|Public|Public|Yes|Yes (Annotations)|Varied (up to 1024x1024)|
|Flickr30k|University of Illinois|Natural language descriptions of images|31K|English|Research Use Only|Public|Yes|Yes (Captions)|Varied (up to 1024x1024)|
|YFCC100M|Yahoo|100 million Creative Commons images from Flickr|100 million|Multilingual|Creative Commons|Public|Yes|Yes (Limited Captions)|Varied|
|SBU Captioned Photos|SBU|Large-scale captioned photo dataset|1 million|English|Non-commercial research only|Public|Yes|Yes (Captions)|Varied|
|DeepFashion|CUHK|Fashion dataset for clothes recognition & synthesis|800K|English|Public|Public|Yes|Yes (Attributes, Captions)|Varied|
|WikiArt|WikiArt|Large collection of artworks with metadata|250K|Multilingual|Creative Commons|Public|Yes|Yes (Labels, Descriptions)|Varied|

