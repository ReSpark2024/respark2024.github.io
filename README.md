# ReSpark: Leveraging Previous Data Reports as References to Generate New Reports with LLMs

Creating data reports is time-consuming, as it requires iterative exploration and understanding of data, followed by summarizing the insights. While large language models (LLMs) are powerful tools for data processing and text generation, they often struggle to produce complete data reports that fully meet user expectations. One significant challenge is effectively communicating the entire analysis logic to LLMs. Moreover, determining a comprehensive analysis logic can be mentally taxing for users. To address these challenges, we propose ReSpark, an LLM-based method that leverages existing data reports as references for creating new ones. Given a data table, ReSpark searches for similar-topic reports, parses them into interdependent segments corresponding to analytical objectives, and executes them with new data. It identifies inconsistencies and customizes the objectives, data transformations, and textual descriptions. ReSpark allows users to review real-time outputs, insert new objectives, and modify report content. Its effectiveness was evaluated through comparative and user studies.

## Demo

<video width="80%" controls loop="" muted="" autoplay="">
    <source src="https://github.com/ReSpark2024/respark2024.github.io/raw/main/assets/demo.mp4">
</video>

## Prompt Used

 * [Prompt for ReSpark system](https://github.com/ReSpark2024/respark2024.github.io/blob/main/assets/system%20prompts.pdf)
 * [Prompt for baselines](https://github.com/ReSpark2024/respark2024.github.io/blob/main/assets/prompts%20for%20baseline.pdf)
