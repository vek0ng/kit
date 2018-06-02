# Kit Project

Think of the Kit project as a company’s standard library, so there should only be one. The packages that belong to the Kit project need to be designed with the highest levels of portability in mind. These packages should be usable across multiple Application projects and provide a very specific but foundational domain of functionality. To this end, the Kit project is not allowed to have a vendor folder. If any of packages are dependent on 3rd party packages, they must always build against the latest version of those dependences.
