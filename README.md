# Public-Hospitals-BuenosAires-Reviews
A data driven story based on Google Reviews about the public hospitals in Buenos Aires that had more consults during 2025.
# Link

# What is this story about?
The five public hospital in Buenos Aires City that had more consults in 2025 and the Google Reviews uploaded about them. Despite concerns about their reliability, they appear prominently in search results.
# Step 1
Google reviews were scrapped using SerpAPI, free version, in order to obtain them. It was 1 csv file per hospital. Then, they were concatenated. This first final file has data about 4355 reviews which have text (rating + comment). After that, it was possible to observe a historical tendence: more positives than negatives reviews. But it changed in 2023.
# Step 2
What happened in 2023? Besides searching for public records about public spending, it was important to know what were saying the negatives reviews since that year. So, categorization with AI was needed.
# Step 3
Focus on the negative reviews 2023 - 2025. They are 748. As their texts aren't so long, but they are a lot, a first human read was done in order to think about possible categories. Then, after deciding which categories suit best, a prompt was created. The first trie obtained a 80.3% of accuracy. This was measured with a handcoded human verification. After changing 4 times the prompt, the accuracy level reached 91.3%. One more try in order to have 95%, but the new prompt wasn't good, so the 91.3% version was the final one.
# Unexplored angles
A detailed one by one work of every comment in order to find particular stories or situations thay may help to detect serious problems.
# Scale possibility
More hospitals. In different regions or provinces.

