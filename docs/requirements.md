\# NewsHub — News Aggregator

\## Initial Software Requirements Document



\*\*Course:\*\* Software Construction and Development  

\*\*Instructor:\*\* Engr. Muhammad Umer Haroon  

\*\*Project Version:\*\* 0.1.0  

\*\*Document Status:\*\* Initial Draft



\## 1. Group Members



| No. | Name | GitHub Username |

|---|---|---|

| 1 | Abdul Samad Orakzai | 0xSamad |

| 2 | Muhammad Mansoor | mansoorauraxai |





\## 2. Problem Statement



People often visit multiple websites to find news about different topics. This can take time and make it difficult to browse news according to personal interests.



NewsHub aims to provide a single, simple interface where users can browse headlines from Technology, Sports, Business, and World news categories. Users will also be able to open the original articles to read the complete news.



\## 3. Project Objectives



\- Collect news headlines from an external news API.

\- Organize news into different categories.

\- Display headlines and available article information in a user-friendly interface.

\- Allow users to open original news articles.

\- Practice software engineering, modular programming, testing, Git, and collaborative development.



\## 4. Intended Users



\- General users interested in current news.

\- Students and readers who want to browse different news categories.

\- People who prefer accessing news headlines through one interface.



\## 5. Functional Requirements



| ID | Requirement | Priority |

|---|---|---|

| FR-01 | The application shall display Technology, Sports, Business, and World categories. | High |

| FR-02 | Users shall be able to select a category. | High |

| FR-03 | The application shall fetch news from an external news API. | High |

| FR-04 | The application shall display available news headlines. | High |

| FR-05 | The application should display article sources, publication dates, descriptions, and images when available. | High |

| FR-06 | Users shall be able to open the original article in a browser. | High |

| FR-07 | The application shall display an appropriate message if news cannot be loaded. | High |

| FR-08 | Users should be able to search news by keyword. | Medium |

| FR-09 | Users should be able to refresh the news list. | Medium |

| FR-10 | Users may be able to bookmark articles for later access. | Low |



\## 6. Non-Functional Requirements



\- \*\*Usability:\*\* The interface should be simple and easy to navigate.

\- \*\*Performance:\*\* News should load within a reasonable time under normal network conditions.

\- \*\*Reliability:\*\* The application should handle API errors and empty results gracefully.

\- \*\*Maintainability:\*\* The code should be organized into understandable modules.

\- \*\*Security:\*\* API keys and other secrets must not be uploaded to the public repository.

\- \*\*Compatibility:\*\* The application should work in a supported desktop web browser.

\- \*\*Portability:\*\* The application should be runnable locally on computers with the required Python dependencies.



\## 7. Initial Product Backlog



| ID | Task | Priority | Status |

|---|---|---|---|

| PB-01 | Create and organize the GitHub repository. | High | In progress |

| PB-02 | Prepare the README and requirements document. | High | In progress |

| PB-03 | Set up the Flask application. | High | Planned |

| PB-04 | Integrate a news API. | High | Planned |

| PB-05 | Implement news categories and headline display. | High | Planned |

| PB-06 | Add original article links and error handling. | High | Planned |

| PB-07 | Implement keyword search and refresh. | Medium | Planned |

| PB-08 | Add optional bookmarking functionality. | Low | Planned |



\*Update task statuses as the project progresses.\*



\## 8. Assumptions



\- Users will have an internet connection to fetch news.

\- A suitable news API will be available.

\- The selected API will provide headlines and article URLs.

\- An API key may be required.

\- News availability will depend on the selected API provider.



\## 9. Constraints



\- The project must be completed within the semester timeline.

\- The team will initially focus on essential features.

\- The application may be limited by API rate limits and free-tier restrictions.

\- The initial application will run locally.

\- Python and Flask are the planned technologies.



\## 10. Known Limitations



\- Some articles may not include images, descriptions, or publication dates.

\- News availability may vary between categories and API providers.

\- API failures or rate limits may temporarily prevent news from loading.

\- The application will link to external websites and will not control their content.

\- Advanced features such as personalized recommendations and user accounts are outside the initial scope.



\## 11. Initial Acceptance Criteria



The first working version should meet these conditions:



1\. The application starts successfully.

2\. Users can select each of the four news categories.

3\. Available headlines are fetched and displayed.

4\. Users can open original articles through their links.

5\. Errors and empty results are handled with understandable messages.

6\. The repository contains setup instructions and project documentation.



\## 12. Team Collaboration



\- All members will contribute using their own GitHub accounts.

\- The team will use meaningful Git commit messages.

\- Tasks will be divided among members and tracked in the product backlog.

\- Changes will be integrated into the shared repository.

\- Requirements and priorities may be updated as development progresses.

\- Git tags will be used to identify important project milestones.



\## 13. Document Review



This document describes the initial requirements for NewsHub. It is intended to guide the first development stage and may be updated as the project evolves.





