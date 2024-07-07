# Multi-step Iterative Automated Domain Modeling with Large Language Models

## Authors
- **Yujing Yang**  
  McGill University, Montreal, Quebec, Canada  

- **Boqi Chen**  
  McGill University, Montreal, Quebec, Canada  

- **Kua Chen**  
  McGill University, Montreal, Quebec, Canada  

- **Gunter Mussbacher**  
  McGill University, Montreal, Quebec, Canada  

- **Dániel Varró**  
  Linköping University, Linköping, Sweden / McGill University, Montreal, Canada
  
## Abstract
Domain modeling, representing the concepts and relationships in a problem domain, is crucial in software engineering. This paper introduces a novel framework to enhance automated domain model generation using Large Language Models (LLMs). Unlike traditional single-step methods, our multi-step approach integrates human knowledge and an iterative process to extract and refine model elements, improving the identification of complex patterns and elements.

## Objectives
This paper aims to improve the performance of *fully automated domain modeling* by including human knowledge and self-reflection. We propose a multi-step iterative automated domain modeling approach with LLMs to extract model elements and complex patterns from a textual-based problem description and construct a domain model. This paper also evaluates the proposed approach on an existing dataset and compares its performance to a single-step approach. Furthermore, this paper also strives to identify the advantages and limitations of the proposed approach for fully automated domain modeling.

## Key Contributions
- **Multi-step automated domain modeling**: Extracts model elements iteratively, leveraging human input at each step.
- **Self-reflection mechanism**: Assesses generated model elements, providing feedback for modifications and removals.
- **Enhanced performance**: Significant improvement in identifying classes, relationships, and complex design patterns compared to single-step approaches.

## Contributions
Given a textual domain description, we present a novel approach for fully automated domain modeling using LLMs. The specific contributions of this paper are the following:

- We propose a multi-step iterative automated domain modeling approach using LLMs combined with human knowledge, including an iterative process to identify best-practice patterns.
- Furthermore, our approach includes a self-reflection mechanism to generate internal feedback according to human knowledge and then integrate the generated feedback into the domain model for improvement.
- We carry out experiments with GPT-4 to evaluate the proposed approach compared to the single-step approach. Specifically, this paper assesses the performance of generating domain models (including classes, attributes, and relationships) and the performance of identifying domain modeling patterns.

## Keywords
domain modeling, large language models, few-shot learning, prompt engineering
