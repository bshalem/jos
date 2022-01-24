# What is JOS?
JOS is a high-quality and sustainable dataset that contains judicial opinion summaries of the US Supreme Court we scraped from FindLaw's public repository, and merged with docket entry meta-data we extracted from SCDB.

The main goal of the dataset is to aid the study of automatic issue-area discovery in opinion summaries, using transformer-based language models pretrained on either a generalized or a legal domain. 

The data is formatted as a collection of json case objects.

# Download JOS
The dataset resides in a single file: [SC_data.json](SC_data.json).

# Paper
More details on the collecting of the data is available in our companion paper:

Avi Bleiweiss. *Issue Area Discovery from Legal Opinion Summaries using Neural Text Processing*. In ICAART, 2022.
 
### Citation
If you use the JOS dataset as part of your work, please cite:
    
     @inproceedings{bleiweiss-2022-icaart,
      title = "Issue Area Discovery from Legal Opinion Summaries using Neural Text Processing",
      author = "Bleiweiss, Avi",
      booktitle = "Proceedings of the Fourteen Conference on Agents and Artificial Intelligence ({ICAART})",
      month = feb,
      year = "2022",
      address = "online",
      publisher = "{SCITEPRESS}",
      pages = "938--944",
    }

