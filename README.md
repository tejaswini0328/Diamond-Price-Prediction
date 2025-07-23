Diamond Price Analysis This project explores how various features of diamonds (such as carat, cut, color, clarity, and size) influence their price. Using visualizations and statistical analysis, we uncover patterns and relationships in the dataset.

Dataset The dataset used is diamonds.csv, which contains 53,940 rows with the following features: Feature Description carat Weight of the diamond cut Quality of the cut (Fair, Good, Very Good, etc.) color Diamond color grade (D to J) clarity Clarity grade (I1 to IF) depth Total depth % table Width of top of diamond relative to widest point price Price in US dollars x, y, z Physical dimensions (length, width, depth) size Calculated as x × y × z (volume of diamond)

Analysis Performed 1.Data Cleaning: Removed missing values and unnecessary columns. 2.Feature Engineering: Created a new size column as volume = x × y × z. 3.Statistical Summary: Generated descriptive statistics for numeric features.

Visual Explorations: Price distribution, Carat vs Price (colored by cut), Price by Cut, Price by Color, Price by Clarity, Size vs Price.

Insights we got from analysis: 1.Carat and Size are the most influential factors on price. 2.Cut, Clarity, and Color also play significant roles but have more subtle impacts. 3.The price distribution is right-skewed, with many diamonds priced below $5,000. 4.Larger diamonds with ideal cuts are significantly more expensive.

How to Run Open the notebook in Google Colab. Upload the diamonds.csv file when prompted. Run all cells to perform the analysis and generate visualizations.

Libraries Used pandas – data manipulation matplotlib – data visualization seaborn – advanced statistical plots
