# Australian-Celebrities-Face-Recognition-with-Transfer-Learning

## Project Description

This project aims to build a deep learning model for recognizing the faces of the top 10 most famous celebrities in Australia. We use transfer learning with the VGG16 model, a popular choice for image classification tasks.

## Dataset

The dataset consists of images of 10 celebrities, collected from various sources.
`Nicole Kidman`: An Oscar-winning actress known for her impressive acting resume.
`Hugh Jackman`: An actor, singer, dancer, and all-round good guy, best known for his long-running role as Wolverine in the X-Men film.
`Mel Gibson`: One of the most successful filmmakers and actors in Hollywood.
`Russell Crowe`: The Gladiator star who still calls Australia home.
`Sam Worthington`: Known for his role in Avatar, which made him an international star.
`Rebel Wilson`: A former comedian who had people rolling in the aisles long before she was a movie star.
`Liam Hemsworth`: Started his career on an Australian soap before moving on to become major actors in Hollywood.
`Simon Baker`: Known for his signature role in TV’s The Mentalist.
`Rupert Murdoch`: A media mogul who has built an empire and spread his business acumen on three continents.
`Cathy Freeman`: The first Aboriginal woman to win a 400 meters sprint in the Olympics.

For each celebrity, we have:

- 20 training images
- 10 validation images
- 10 testing images

This distribution ensures that our model has enough data to learn from and yet can be validated and tested effectively.

## Model

We use the VGG16 model as the base model and add a few layers on top to tailor it to our task. The VGG16 model has been pre-trained on the ImageNet dataset, which allows us to leverage learned features for our specific task.

## Training

The model is trained using the training images, with validation performed using the validation images. This allows us to tune the model's parameters for optimal performance.

## Testing

Finally, the model's performance is evaluated on the testing images. This gives us an unbiased estimate of how well our model is likely to perform on unseen data.

## Results

The results section will be updated with the model's performance metrics once the model has been trained and tested.

## Future Work

We plan to continually update the model as more data becomes available. We also aim to explore other architectures and training strategies to further improve the model's performance.

## Acknowledgements

We would like to thank all the contributors who have made this project possible. Your efforts are greatly appreciated.
