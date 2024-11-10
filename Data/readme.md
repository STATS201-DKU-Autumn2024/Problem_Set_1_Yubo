# AiGen-FoodReview Dataset

The AiGen-FoodReview dataset contains machine-generated and human-authored restaurant reviews gathered from social media. This dataset includes textual reviews alongside various computed readability and linguistic metrics, providing a multimodal foundation for analyzing and distinguishing between human and AI-generated content. The dataset serves as a valuable resource for studies in AI-generated content detection, sentiment analysis, and computational social science.

*Citation: Gambetti, Alessandro, and Qiwei Han. "AiGen-FoodReview: A Multimodal Dataset of Machine-Generated Restaurant Reviews and Images on Social Media." Proceedings of the International AAAI Conference on Web and Social Media. Vol. 18. 2024.*

## Data Dictionary

| Variable                    | Description                                               |
|-----------------------------|-----------------------------------------------------------|
| ID                          | Unique identifier for each review                          |
| text                        | Review text                                               |
| label                       | Binary label indicating machine-generated (1) or human (0)|
| automated_readability_index | Automated readability index score of the review text      |
| difficult_words             | Count of difficult words in the review                    |
| flesch_reading_ease         | Flesch reading ease score of the review                   |
| gunning_fog                 | Gunning Fog index score for readability                   |
| words_per_sentence          | Average words per sentence in the review                  |
| reading_time                | Estimated reading time for the review (in seconds)        |
| ppl                         | Perplexity score for the text                             |
| bright                      | Brightness of associated images                           |
| cont                        | Content density of the images                             |
| warm                        | Warmth value in color metrics                             |
| colorf                      | Colorfulness metric                                       |
| sd                          | Standard deviation of colors                              |
| cd                          | Color dominance metric                                    |
| td                          | Text dominance metric                                     |
| diag_dom                    | Diagonal dominance metric                                 |
| rot                         | Rotation angle metric                                     |
| hpvb                        | Horizontal pixel variance block                          |
| vpvb                        | Vertical pixel variance block                            |
| hcvb                        | Horizontal color variance block                          |
| vcvb                        | Vertical color variance block                            |
| sat                         | Saturation metric                                         |
| clar                        | Clarity of the image                                      |

---
