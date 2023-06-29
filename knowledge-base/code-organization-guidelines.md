# Code organization guidelines
Code organization guidelines define how to organize code base and maintain it. Primarily the code base is stored in [GitHub](https://github.com/) repositories of [TB-CORP](https://github.com/TB-CORP) organization. The guidelines are about storing code, not writing it. Brands, sub-brands (next 'brands') and repositories under [TB-CORP](https://github.com/TB-CORP) organization should follow these guidelines.

---

## Contents
- [Introduction](#code-organization-guidelines)
- [Concept](#concept)
- [Guidelines](#guidelines)
- [See also](#see-also)

## Concept
The concept behind is to define namespaces for repositories to quickly understand their relationship to the code base without having to explore and open other repositories. This may reduce the flexibility of the organizational structure, but it sets the right mindset for organization members to create and organize projects, makes the process faster, defines a clear hierarchy and eliminates the need to think about how to add a new project. As the organization grows, the code base will not devolve into an uncontrollable mess.

## Guidelines
Refer existing projects to easier understand the guidelines. See, [TB-CORP repositories](https://github.com/orgs/TB-CORP/repositories).

- Each project must have `Name`, `Alt`, `Code`. Name is the complete name of a project with a full interpretation of its namespace. Alt is an alternative project name, so as not to specify its complete name. Code is an abbreviated name. Name, alt and code must be specified in the beginning of the README file of the project. Alt name for brands is optional.
- The name of a project should include the name of its brand and other projects from which it originates or of which it is a part.
- Repository must be named the same as its alt name. If there is more than a word in the alt, its should be hyphen-separated case.

## See also
- [Common terms](./common-terms.md)

#knowledge-base