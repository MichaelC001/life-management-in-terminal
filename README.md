# life management workflow in terminal
### 1. Principle
- **[Philosophy]** This workflow is just a methodology and philosophy, you can develop your own workflow based on it, you don't necessarily have to use the same software or tools as me.
- **[Purpose]** The purpose of this workflow is to **solve problems** in my life and **develop my passions** through **lifelong learning**.

### 2.Hark link and soft link
The core tool used in this workflow is the system build-in function: hard link and soft link.<br />

**hard link** <br />
```
ln original_file new_file
```
This command creates a new link to the original file, so that any changes made to either file will be **automatically synchronized**, resulting in both files being **exactly the same**.<br />
The hard link only works for files.Delete one file will not affect another linked file.

### 3.Journal folder structure and tag system
- My workflow is based on daily Journal.
- It is a file based system, all notesmare orgnized in folder_structure <br />
**one folder one day**, **one entry one file**.
<p align="left">
<img src="/src/folder_structure.png" alt="Journal folder structure]" width="500">
</p>
**Tag system**
Yes, we can use hard links to build a tag system. By assigning tags to files through hard links, we can easily organize and access files by their tags. This is because each hard link behaves as a separate file that retains the same content as the original file, but with a different name or location. Thus, multiple tags can be assigned to a single file by creating multiple hard links to that file with different tag names.

