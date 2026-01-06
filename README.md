The idea to create this repository came from my experience working across different types of projects. 
Although each project is unique, they often share common patterns: clear strengths, recurring areas for improvement, approaches that worked well, and gaps that need to be addressed to keep the work sustainable over time.

There is a growing focus on using AI to make tasks faster and more automated. However, without a solid understanding of the problem and the underlying scientific principles, AI becomes little more than a shot in the dark - often leading to misleading results rather than real insights.

For this reason, I believe scientific criteria must remain central to any analytical workflow: critical evaluation, interpretability, reproducibility, and the ability to clearly explain what is being done and why.

This repository shares documentation and review practices that have worked well for me across scientific and data-driven projects. I hope these examples can help others structure, evaluate, and communicate their analyses more effectively.

## Overview

This repository includes four examples of scientific analysis documentation and technical review:

- [Gene expression analysis](https://github.com/CarolPacifico0/scientific-documentation-and-review/tree/main/AI-generated);  
- [Data curation and quality control (QC) of biological data](https://github.com/CarolPacifico0/scientific-documentation-and-review/tree/main/Data%20Curation%20and%20QC); 
- [AI-generated analyses and their critical review](https://github.com/CarolPacifico0/scientific-documentation-and-review/tree/main/AI-generated);
- [Baseline in Statistical Programming](https://github.com/CarolPacifico0/scientific-documentation-and-review/tree/main/SP%20baseline)

**Note:** No sensitive data are shared in this repository. All examples are illustrative and do not include data analyzed as part of professional work or collaborations.

Without further ado, let's move on.

## Defining the question

Every analysis should begin with a clear and well-defined central question or objective.
Examples of such guiding questions are included in each analysis documentation within this repository.

Once the question is defined, it is essential to stay focused on it throughout the analytical process.

It can be very tempting to explore additional patterns, correlations, or side questions along the way. While this exploratory impulse is natural and often valuable, it frequently leads to a common pitfall: by the end of the analysis, many interesting questions may have been answered, except the one originally posed.

This repository emphasizes the importance of discipline in analytical reasoning.
Don’t fall for it!! 

## Documentation Principles

Good scientific documentation serves more than a descriptive purpose. It should:

- Clearly state objectives, assumptions, and limitations;
- Make analytical decisions explicit and traceable;
- Allow others to understand why certain methods were chosen, not only how;
- Support reproducibility, review, and future maintenance.
  
## Common pitfalls

Once an analysis has started, several critical questions must be addressed early:

**How were the data collected?**

Hospital records, laboratory experiments, public databases, simulated data?

**Was the data collection standardized?**

Are variables consistently defined across sources?

**Are formats and conventions clearly understood?**

For example: is the date format dd/mm/yyyy or mm/dd/yyyy?
*(As a Brazilian, I still need to consciously pause and check this.)*

**Do the results make biological sense?**

A statistically significant result without biological plausibility is a red flag.
If Gene A is expressed 30% more than Gene B, what does this mean in biological or clinical context?


## AI in Scientific worflows

Well... sensitive topic here.

AI can dramatically accelerate analytical tasks, assist with pattern recognition, and support exploratory analyses. However, speed without understanding is dangerous. **If the analyst does not clearly understand the underlying data, the assumptions of the methods, and the scientific context, then AI-assisted analysis becomes a shot in the dark**. 

I am sharing what has worked for me, with the hope that it may help others build analyses that are not only faster, but also sound, interpretable, and scientifically rigorous.
