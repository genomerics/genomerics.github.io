---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Who we are

Genomerics provides data science, bioinformatics and software services, with a focus on small and medium enterprises in the biotech space. Based in the innovation hub of Cambridge UK, we've worked with clients in Cambridge and London and remotely with clients in the EU and the US.

# What we do

We specialize in developing robust, production-ready data solutions for complex computational challenges. Our expertise spans algorithm development, machine learning implementation, and custom software engineering for scientific applications.

While our work is typically conducted under confidentiality agreements, here are some things we've implemented during recent projects:


| Project Type | Technologies deployed |
| --- | --- |
| Encapsulated workflows for processing Oxford Nanopore sequencing data | Docker, AWS, Nextflow, python, bash, bcftools/samtools/htslib |
| Building image processing pipelines | Python, OpenCV, matplotlib |
| Algorithm development for PacBio HiFi sequencing data | C/C++ |
| Machine learning pipeline productization | Python, scikit-learn, MLFlow, hydra |
| Large language models for sequence classification | Python, DNABert |

# Our Approach

We combine data science expertise with professional software engineering practices to deliver solutions that are not just proof-of-concept but production-ready. Whether you're just starting with next-generation sequencing or looking to scale existing operations, our deep understanding of both the technical and biological aspects allows us to tailor effective solutions to your specific challenges.

# How we work

* Short-term projects: After an initial consultation to understand your requirements, we provide a detailed proposal with clear deliverables and timeline.
* Longer-term contracts: We can integrate with your team or work independently to provide ongoing support and development.

We have full employers' liability insurance with coverage extending worldwide, including the US.

# Get In Touch
Ready to discuss how Genomerics can help your business achieve its goals?

* Connect via [LinkedIn](https://www.linkedin.com/in/coxtonyj/) 
* Schedule a call with [Calendly](https://calendly.com/anthony-j-cox/30min) 


# Blog posts

Content coming soon!
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
