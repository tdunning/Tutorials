---
title: Contribute
permalink: /docs/contribute/
---

Do you want to contribute to SU2 with a tutorial? It's easy! Just create a fork of the [Tutorials repository](https://github.com/su2code/Tutorials), write your tutorial and open a pull request. 

## Writing content

The documentation in this site is stored under the `_docs` folder. To add your contributions:

**1.** Create a new subfolder in `_docs/` as `_docs/Your_Folder_Name`, where you will store your subgroup of tutorials. 

**2.** Add a new Markdown file inside the subfolder, as `_docs/Your_Folder_Name/Your_Tutorial.md`. Add the following [front matter](https://jekyllrb.com/docs/frontmatter/) to your file:

```
---
title: Your Tutorial Title
permalink: /docs/Your_Folder_Name/Your_Tutorial/
---

I'm contributing to SU2!
```

**3.** Add the tutorial pagename to the `_data/docs.yml` file, in order to list it in the navigation panel:

```
- title: Your Subgroup of Tutorials 
  docs:
  - Your_Tutorial
```

**4.** Create a folder with the format `TXXX_Your_Tutorial_Name`, where `XXX` is a number which follows the sequence of tutorials available.

**5.** Add your `config.cfg`, `mesh.su2` and any other auxiliary files to the folder `TXXX_Your_Tutorial_Name`.

**6.** When you are ready, submit a pull request to the **develop** branch of the [repository](https://github.com/su2code/Tutorials)... and it's all done! Thanks for your contribution!
