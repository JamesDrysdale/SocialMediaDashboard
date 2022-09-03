# Social Media Dashboard with Theme Switcher

## Functional Requirements and notes

The user should be able to:

- [ ] Toggle color theme to their preference
    - [ ] Initially load the appropriate theme depending on their system preference
    - [ ] Select Light Mode 
    - [ ] Select Dark Mode
- [ ] View the optimal layout for the site depending on their device's screen size
- [ ] See hover states for all interactive elements on the page

### Things to consider:

- Switching between light/dark modes via JS
- Potentially using a 3 option toggle: light / dark / system preference <br />
- Having the app take system preference by default, and user can override theme settings with toggle
- What HTML markup will I need to use to ensure the app adheres to good UX and accessibility standards?

#### Styling Considerations

How do I switch between light and dark mode? I.E. using CSS variables?

If the toggle option needs three values and therefore three positions on a scale as light/dark mode toggles can break if they do not account for system preference, which would take precidence. 

❓ ***Will I need CSS variables? How do I use them?***

**References**: 
- [CSS Tricks: Updating a CSS variable with Javascript](https://css-tricks.com/updating-a-css-variable-with-javascript)

<hr />

❓ ***What is prefers colour scheme media query?***

***References***: 
- [MDN: prefers-color-scheme](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme)


#### Accessibility

There should be some screen-reader only text for card titles/usernames, so that users can tell contextually that it's a twitter handle or number of FaceBook likes. 

Semantic tags should be used, and care given to utilise the correct Heading tags.

Radio inputs should have a fieldset and a legend structure. The legend should describe the nature of the options: e.g. Colour Theme

***Refrerences***:
- [Accessibility Developer Guide](https://www.accessibility-developer-guide.com/)
- [ADG: Hiding Elements Visually by Moving them Off-screen](https://www.accessibility-developer-guide.com/examples/hiding-elements/visually/)





