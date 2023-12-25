# Gemini vs GPT-4V: A Preliminary Comparison and Combination of Vision-Language Models Through Qualitative Cases




## 🤖 Demos
### Section 2: Image Recognition and Understanding
This section focuses on basic recognition and understanding of image content, excluding further inference. It covers tasks such as landmark, food, logo, abstract image recognition, autonomous driving scene understanding, fake information detection, difference spotting, and object counting. These are fundamental tasks of the first layer. The section comprises 9 subsections.

### 2.1 Basic Object Recognition
Testing the models' basic object recognition and description capabilities. GPT-4V and Gemini both accurately recognize basic objects and provide textual descriptions without significant differences.
<img src="./2.1_Basic_object_Recognition_1.png" width="1000" />

### 2.2 Landmark Recognition
Both models excel in accurately recognizing landmarks, but GPT-4V generates concise descriptions, while Gemini tends to provide more detailed narratives for tourist attractions, even indoors, including other pictures of the sites and related information links.
<img src="./2.2_Landmark_Recognition_1.png" width="1000" />

### 2.3 Food Recognition
Both models demonstrate the ability to recognize a wide variety of dishes, enhancing their recognition of details such as ingredients, decorations, and cooking techniques in food images. The conclusion is similar to that of landmark recognition.
<img src="./2.3_Food_Recognition_1.png" width="1000" />

### 2.4 Logo Recognition
Both models successfully recognize logos and provide comprehensive descriptions, capturing information on design, color, shape, and symbolic representation.
<img src="./2.4_Logo_Recognition_1.png" width="1000" />

### 2.5 Abstract Image Recognition
While GPT-4V provides reasonable answers, Gemini's responses seem less logical in recognizing abstract images like Tangram puzzles, possibly due to being trained on all stitched images.
<img src="./2.5_Abstract_Image_Recognition_1.png" width="1000" />

### 2.6 Scene Understanding (Autonomous Driving)
Both models are adept at providing detailed descriptions of autonomous driving scenes and objects. In the first example, Gemini's description shows a minor error.
<img src="./2.6_Scene_Understanding_1.png" width="1000" />

### 2.7 Counterfactual Examples (Fabricated Objects)
This involves providing a factual description related to the scenes and objects presented in the image, even when the textual prompt asks the model to find non-existent objects in the picture. Both models manage this well.
<img src="./2.7_Counterfactual_Examples_1.png" width="1000" />

### 2.8 Object Counting
The task is to count the number of fruits in a picture. Both models need improvement in counting. Compared to GPT-4V, Gemini's counting ability is relatively weaker, likely due to its weaker multimodal memory performance, preventing it from being guided to the correct answer.
<img src="./2.8_Object_Counting_1.png" width="1000" />

### 2.9 Spot the Differences
This tests the models' ability to spot differences between two pictures. Both GPT-4V and Gemini have limitations in this area, with GPT-4V being somewhat more accurate.
<img src="./2.9_Spot_the_Differences_1.png" width="1000" />



### Section 3: Text Recognition and Understanding in Images
Focusing on text recognition within images (including OCR) such as scene text, mathematical equations, and text in charts and tables, this section avoids further inference of the text content. It's part of the first basic layer of tasks and includes 9 subsections.

### 3.1 Scene Text Recognition
Extracting text and numbers from scenes like stock market boards and outdoor shop signs. Both models show proficiency in recognizing scene text in many complex situations.
<img src="./3.1_Scene_Text_Recognition_1.png" width="1000" />

### 3.2 Equation Recognition
Converting equations in images to LaTeX format, both GPT-4V and Gemini struggle with equation recognition, especially when the formulas become complex.
<img src="./3.2_Eqation_Recognition_1.png" width="1000" />

### 3.3 Chart Text Recognition
Demonstrating text recognition and extraction from table images. Overall, GPT-4V's abilities lag behind those of Gemini Pro in this task.
<img src="./3.3_Chart_Text_Recognition_2.png" width="1000" />




### Section 4: Image Inference Abilities
Beyond basic image recognition, this part involves higher-level reasoning, including understanding humor and scientific concepts, detective work, image combination, pattern finding in intelligence tests, and emotional understanding and expression. This is the second level of tasks requiring further inference beyond basic recognition. There are 6 subsections.
### 4.1 Humorous Image Understanding, Memes
In understanding humor in images, both GPT-4V and Gemini demonstrate satisfactory abilities, comprehending the humor embedded in Memes.
<img src="./4.1_Humorous_Image_Understanding_1.png" width="1000" />

### 4.2 Multimodal Knowledge and Commonsense
Both GPT-4V and Gemini can understand scientific common sense and gather necessary information to answer questions. In the first example, there's a missing detail in Gemini's description.
<img src="./4.2_Multimodal_Knowledge_and_Commonsense_1.png" width="1000" />

### 4.3 Detective Reasoning Ability
Given an image of a house, the task is to infer the homeowner's personality. Both GPT-4V and Gemini make good inferences based on common sense.
<img src="./4.3_Detective_Reasoning_Ability_1.png" width="1000" />

### 4.4 Association of Parts and Objects
This involves combining three parts of a person dressed in a bag over their head and body. Both GPT-4V and Gemini know how to combine these parts logically. GPT-4V provided a more satisfying answer, giving the order of the sub-images to form one image.
<img src="./4.4_Association_of_Parts_and_Objects_1.png" width="1000" />

### 4.5 Intelligence Tests
For pattern finding problems in the Wechsler Adult Intelligence Scale (WAIS), Gemini performs poorly, indicating limited ability in recognizing and comparing multiple images.
<img src="./4.5_Intelligence_Tests_1.png" width="1000" />

### 4.6 Emotional Intelligence Tests (Emotional Understanding and Output)
In understanding the emotions expressed in pictures, both GPT-4V and Gemini grasp how different visual content can evoke human emotions.
Emotional Intelligence Tests
<img src="./4.6_Emotional_Intelligence_Tests_1.png" width="1000" />




### Section 5: Text Inference in Images
Beyond basic image recognition, this part involves higher-level reasoning. It includes understanding humor and scientific concepts, detective work, image combination, intelligence test pattern finding, and emotional understanding and expression. This is the second level of tasks requiring further inference beyond basic recognition. There are 3 subsections.

### 5.1 Visual Math Ability
For simple math problems, both GPT-4V and Gemini can provide accurate answers.
<img src="./5.1_Visual_Math_Ability_1.png" width="1000" />

### 5.2 Table & Chart Understanding and Reasoning
Here, the models demonstrate their understanding of flowcharts. In this example, both models can convert flowcharts into Python code.
<img src="./5.2_Table_Chart_Understanding_and_Reasoning_1.png" width="1000" />

### 5.3 Document Understanding And Reasoning
Shown here is an apartment floor plan. Both models provide accurate answers, with Gemini's response being more complete and organized.
<img src="./5.3_Document_Understanding_And_Reasoning_1.png" width="1000" />




### Section 6: Integrated Understanding of Images and Text
Beyond basic image recognition, this part involves higher-level reasoning, including understanding humor and scientific concepts, detective work, image combination, intelligence test pattern finding, and emotional understanding and expression. This is the third level focusing on integrated understanding of text and images. There are 2 subsections.
### 6.1 Interleaved Image-Text Inputs
The image involves calculating taxes from multiple bills. GPT-4V can accurately provide outputs, while Gemini struggles with responses to connected images but performs well in providing individual answers for each image.
<img src="./6.1_Interleaved_Image_text_Inputs_1.png" width="1000" />

### 6.2 Text to Image Generation Guidance
Improving text-to-image model SDXL prompts through self-reflection, GPT-4V acknowledges the error in the initial prompt not mentioning the dog's breed and makes a correct revision. Gemini's generated text prompt is better, mentioning the dog's breed.
<img src="./6.2_Text_to_Image_Generation_Guidance_1.png" width="1000" />




### Section 7: Object Localization
Emphasizing object localization abilities, models are required to provide relative coordinates (top-left and bottom-right corners) of specified objects. This includes focusing on outdoor objects, like cars in parking lots, and abstract image localization. There are 2 subsections.

### 7.1 ObjectVLocalization in Real World
Targeting the identification of a car in a parking lot, following an example of locating a beer bottle. Both GPT-4V and Gemini understand coordinates to generate visual indication outputs.
<img src="./7.1_Object_localization_in_real_world_2_1.png" width="1000" />

### 7.2 Abstract Image Localization
Targeting the location of a part of an abstract object, the Tangram. By prompting them to output the corners of the location box, GPT-4V can localize the head of the abstract goose, while Gemini fails in this scenario.
<img src="./7.2_Abstract_Image_Localization_1.png" width="1000" />



### Section 8: Temporal Video Understanding
Assessing the models' understanding of temporality through keyframe evaluation, this part includes two tasks: understanding video sequences and focusing on keyframe ordering. There are 2 subsections.

### 8.1 Action Recognition
Given a series of continuous actions, both GPT-4V and Gemini can generate correct understandings.
<img src="./8.1_Action_Recognition_1.png" width="1000" />

### 8.2 Temporal_Ordering
The sushi-making process is unordered, only GPT-4V finds the correct order, while Gemini fails in this scenario.
<img src="./8.2_Temporal_Ordering_1.png" width="1000" />




### Section 9: Multilingual Capabilities
A comprehensive assessment of the ability to recognize, understand, and generate content in multiple languages. This includes recognizing non-English content in images and expressing information in other languages. There are 2 subsections.

### 9.1 Multilingual Image Description
Both GPT-4V and Gemini can describe images in different languages.
<img src="./9.1_Multilingual_Image_Description_1.png" width="1000" />

### 9.2 Multilingual Scene Text Recognition
Both GPT-4V and Gemini can recognize the scene text in these three images.
<img src="./9.2_Multilingual_Scene_Text_Recognition_1.png" width="1000" />




### Section 10: Industry
Demonstrating various application scenarios of large-scale multimodal models, this section aims to showcase more possibilities to the industry and provide innovative ideas. Multimodal large models can be customized according to specific field requirements. Here, we present seven sub-fields.

### 10.1 Industry: Defect Detection
Performing defect detection on industrial assembly lines. Both models can detect defects in objects within images quite accurately. However, it's worth noting that Gemini provides more details in such tasks.
<img src="./10.1_Industry_Defect_Detection_1.png" width="1000" />

### 10.2 Industry: Grocery Checkout
Self-checkout applications in supermarkets. While GPT-4V provides more comprehensive and detailed results, some errors exist. On the other hand, Gemini identifies only four objects correctly, even including corresponding images for each item. This shows that while GPT-4V offers breadth in discovery, Gemini offers accuracy, displaying different strengths in performing such tasks.
<img src="./10.2_Industry_Grocery_Checkout_1.png" width="1000" />

### 10.3 Industry: Auto Insurance
Judging the extent of damage at a car accident scene. Both demonstrate their ability to conduct comprehensive, detailed, and accurate damage assessments.
<img src="./10.3_Industry_Auto_Insurance_1.png" width="1000" />

### 10.4 Industry: Customized Captioner
First inputting individual object pictures and names as prompts to the model, then inputting a complete scene for the model to describe the relative positions of various objects. GPT-4V provides more comprehensive, accurate, and organized descriptions, while Gemini performs poorly, failing to recognize the existence of a snail shell in the left image and incorrectly describing the snail's position. This shows GPT-4V's excellence in providing detailed and precise descriptions.
<img src="./10.4_Industry_Customized_Captioner_1.png" width="1000" />

### 10.5 Industry: Evaluation Image Generation
Testing the match between text prompts and generated images. Both models accurately describe the image content and provide corresponding explanations and consistent scores. Notably, Gemini provides more detailed reasons for its evaluations.

<img src="./10.5_Industry_Evaluation_Image_Generation_1.png" width="1000" />

### 10.6 Industry: Embodied Agent
In Embodied AI applications, GPT-4V provides the correct answer with a clear and concise explanation. In contrast, Gemini's response is entirely incorrect.
<img src="./10.6_Industry_Embodied_Agent_1.png" width="1000" />

### 10.7 Industry: GUI Navigation
Here, the example is using a PC web search engine to search for a Mapo tofu recipe, starting from a freshly booted computer interface, guided step by step through a multimodal model. Only the first step is presented here.
<img src="./10.7_Industry_GUI_Navigation_1.png" width="1000" />



### Section 11: Integrating GPT-4V and Gemini
In this section, we explore how to combine GPT-4V and Gemini, leveraging their respective strengths, with two subsections.

### 11.1 Product Identification and Recommendation
First, we use GPT-4V to describe all objects in a picture. Then, the answer from GPT-4V is used as part of the input for Gemini to recommend links for similar products.
<img src="./11.1_Integrated_use_of_GPT4V_and_Gemini_1.png" width="1000" />

### 11.2 Multi-Image Recognition and Story Generation
Initially, GPT-4V is employed to describe all the scenes contained in a picture. Following this, Gemini is used to generate a long narrative in a specific style based on these descriptions.
<img src="./11.2_Integrated_use_of_GPT4V_and_Gemini_1.png" width="1000" />










