## Table Of Contents:

1. [Design & Planning](#design-&-planning)
   - [User Stories](#user-stories)
   - [Wireframes](#wireframes)
   - [Typography](#typography)
   - [Colour Scheme](#colour-scheme)
2. [Features](#features)

   - [Navigation](#Navigation)
   - [Footer](#Footer)
   - [Home page](#Home-page)
   - [Other features](#Other-features)

3. [Technologies Used](#technologies-used)
4. [Testing](#testing)
5. [Bugs](#bugs)
6. [Deployment](#deployment)
7. [Credits](#credits)

## Design & Planning:

### User Stories

| **User Story**                          | **Acceptance Criteria**                                                                                                                                                                                                                           | **Tasks**                                                                                                                                                                                                        | **Label** |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Responsive Layout                       | - Content reorganises itself at various breakpoints.<br>- No horizontal scrollbars appear on any common screen size.<br>- Text and buttons remain legible and tappable.                                                                           | - Adopt a grid-based layout that responds to mobile, tablet, and desktop widths.<br>- Adjust typography and spacing for readability on smaller screens.<br>- Test layout integrity using Chrome Developer Tools. | Must      |
| Clear Main Navigation Menu              | - A persistent nav bar appears at the top of the page, and stays visible as users scroll.<br>- Users can click or tap any link to jump directly to that section.<br>- On narrow screens, the menu collapses.<br>- Current section is highlighted. | - Design an intuitive menu structure mapping to each page section.<br>- Implement responsive behaviour for hamburger toggle on small screens.<br>- Add smooth scrolling and active-link highlighting.            | Must      |
| Calming Hero Section                    | - A prominent hero area displays an uplifting headline and sub-headline.<br>- Background imagery or calming colour fills the space without obscuring text.<br>- Text remains legible on all devices.                                              | - Select or create a soothing background and supportive headline.<br>- Style the hero for clarity and positive tone.<br>- Verify readability across viewports.                                                   | Must      |
| Accessibility Available Throughout Site | - All text and interactive elements meet minimum contrast ratios.<br>- Every image or icon has a descriptive text alternative.<br>- Semantic HTML markup supports accessibility.                                                                  | - Define and apply an accessible colour palette.<br>- Audit and add alt text for images.<br>- Use semantic HTML structures.                                                                                      | Must      |
| Information Cards for Tips & Issues     | - Tips appear in consistent card-style groupings under clear headings.<br>- Cards display multiple per row on wide screens and stack on narrow ones.<br>- Text within cards is concise and wraps correctly.                                       | - Design reusable card templates.<br>- Organise cards under headings (e.g. "Stress", "Anxiety").<br>- Ensure responsive card layout.                                                                             | Should    |
| Resource Links Styled as Buttons        | - Resource links appear as prominent buttons.<br>- Buttons are evenly spaced and responsive.<br>- Links open in new tabs.                                                                                                                         | - Define button styles for external links.<br>- Lay out buttons in a clean grid.<br>- Verify tap areas and link behaviour across devices.                                                                        | Should    |
| Positive Affirmations Section           | - Section displays multiple uplifting quotes.<br>- Quotes are visually distinct and spaced clearly.<br>- Section fits with overall design.                                                                                                        | - Curate uplifting messages.<br>- Design and position the affirmations block.<br>- Fine-tune typography and spacing.                                                                                             | Could     |
| Media Play/Pause Controls               | - Embedded media includes visible play/pause controls.<br>- Playback is user-initiated.<br>- Controls are keyboard and touch accessible.                                                                                                          | - Embed media with standard controls.<br>- Disable autoplay.<br>- Test accessibility across devices.                                                                                                             | Could     |

### Wireframes

A larger-scale image of the wireframes can be found [here](documentation/images/MindEase%20Wireframe.png)
![Wireframes depicting rough layout for the site](documentation/images/MindEase%20Wireframe%20(Smaller).png)

### Typography

Google fonts have been chosen to keep to a warm and inviting aesthetic, while maintaining the professionalism of the website:

- Logo: Alata
- Headings: Libre Franklin
- Body: Cabin

### Colour Scheme

![Color palette swatch showing the colors used throughout the site](documentation/images/Colour%20Palette%20Swatch.png)
![Mock-up design on how the colors chosen will work within the site](documentation/images/Colour%20Palette.png)

## Features:

Explain your features on the website,(navigation, pages, links, forms.....)

### Navigation

### Footer

### Other features

## Technologies Used

HTML
CSS
Bootstrap
Git
Github

## Testing

Important part of your README!!!

### Google's Lighthouse Performance

Screenshots of certain pages and scores (mobile and desktop)

### Browser Compatibility

Check compatability with different browsers

### Responsiveness

Screenshots of the responsivness, pick few devices (from 320px top 1200px)

### Code Validation

Validate your code HTML, CSS (all pages/files need to be validated!!!), display screenshots

### Manual Testing user stories or/and features

Test all your user stories, you an create table
User Story | Test | Pass
--- | --- | :---:
paste here you user story | what is visible to the user and what action they should perform | &check;

- and attach screenshot

## Bugs

List of bugs and how did you fix them

## Deployment

#### Creating Repository on GitHub

- First make sure you are signed into [Github](https://github.com/) and go to the code institutes template, which can be found [here](https://github.com/Code-Institute-Org/gitpod-full-template).
- Then click on **use this template** and select **Create a new repository** from the drop-down. Enter the name for the repository and click **Create repository from template**.
- Once the repository was created, I clicked the green **gitpod** button to create a workspace in gitpod so that I could write the code for the site.

#### Deloying on Github

The site was deployed to Github Pages using the following method:

- Go to the Github repository.
- Navigate to the 'settings' tab.
- Using the 'select branch' dropdown menu, choose 'main'.
- Click 'save'.

## Credits

#### Code and Text Content

#### Media

- Images found through [Pexels](http://www.pexels.com).
  - MindEase Logo - Photo by Tara Winstead: https://www.pexels.com/photo/illustration-of-a-head-and-butterflies-around-the-scalp-and-inside-the-brain-8849272/

#### AI Use

- Removal of background on logo image.
- Finding fonts that fit the project.
- No AI used for image creation or code snippets.

#### Acknowledgement

- [Coolors](https://coolors.co/) used for color palette creation.
