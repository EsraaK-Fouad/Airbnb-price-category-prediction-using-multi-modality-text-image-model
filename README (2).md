# Airbnb-price-category-prediction-using-multi-modality-text-image-model.

- One of the biggest problems when people prepare to post a new listing on airbnb is, how much should one ask for? Of course the most intuitive way is to check how other similar postings price their apartment/house. So in this assignment, we are going to predict the listing price based on the listing characteristics 🔥🔥, in this way to optimize user experience and lower the bar to be a new host😍 !

- Predicting the actual price could be simple (well you can just go search online 👍), so we cut the pricing into three different bins for classification 😂. For each listing, we recommend a pricing range to the new host rather than a fix price (how nice is that!). So we define three categories: beginner, plus, premium based on the created listing. Respectively we use 0, 1, 2 to denote these three categories.

- This is a multimodality task which is to estimate the price of an Airbnb listing using multi class classification based on the photo and description provided.
- 
- The dataset contains listings of different areas in Montreal during 2019. It comes with rich information for each listing, including a link to the thumbnails etc. we will follow a multi-objective (multi-task) multi-modality solution.
