In this assignment let's build a **Faqs App** 

### Refer to image below:

<br/>
<div style="text-align: center;">
refer image to understand this application
https://assets.ccbp.in/frontend/content/react-js/faqs-output-v2.gif


<img src="https://assets.ccbp.in/frontend/content/react-js/faqs-output-v2.gif" alt="faqs-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)" />

</div>

<br/>

### Design Files

- [Extra Small (Size < 576px), Small (Size >= 576px), Medium (Size >= 768px)](https://assets.ccbp.in/frontend/content/react-js/faqs-sm-output.png)

- [Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/faqs-lg-output.png)


### Project Set Up Instructions

- Download dependencies by running `npm install`
- Start up the app using `npm start`

### Project Completion Instructions

#### Add Functionality

The app must have the following functionalities

- When the plus icon is clicked in the FAQ
    - The answer to the FAQ should be visible to the user.
    - The plus icon should change to a minus icon.
- When the minus icon is clicked in the FAQ
    - The answer to the FAQ should be hidden to the user.
    - The minus icon should change to a plus icon.
- The `FaqItem` component will receive the details of the faq in the prop `faqData`.
- Each faq object will have the following properties.

  | Key          | Data Type |
  | -----------  | --------- |
  | id           | Number    |
  | questionText | String    |
  | answerText   | String    |

- The value of the key `id` should be used as a key to the `FaqItem` component.


- Your task is to complete the implementation of
  - `src/App.js`
  - `src/App.css`
  - `src/components/FaqItem/index.js`
  - `src/components/FaqItem/index.css`

> #### Important Note
>
> **The following HTML attributes are required for the HTML image elements for the tests to pass**
>
> - The HTML image element to display the plus icon image should have the HTML
>   attribute `alt` value as `plus`
> - The HTML image element to display the minus icon image should have the HTML
>   attribute `alt` value as `minus`

### Quick Tips

- The cursor CSS property sets the type of mouse cursor, if any, to show when the mouse pointer is over an element. Use the CSS property cursor with a value `pointer` to indicate a link.
- An outline is a line that is drawn around an element, outside the border. The outline CSS shorthand property sets all the outline properties. Use the CSS property `outline` with value `none` to hide all the outline properties.


### Resources

#### Images

- [https://assets.ccbp.in/frontend/react-js/faqs-plus-icon-img.png](https://assets.ccbp.in/frontend/react-js/faqs-plus-icon-img.png)
- [https://assets.ccbp.in/frontend/react-js/faqs-minus-icon-img.png](https://assets.ccbp.in/frontend/react-js/faqs-minus-icon-img.png)

#### Colors

<div style="background-color: #cb8805; width: 150px; padding: 10px; color: white">Hex: #cb8805</div>
<div style="background-color: #52606d; width: 150px; padding: 10px; color: white">Hex: #52606d</div>
<div style="background-color: #9aa5b1; width: 150px; padding: 10px; color: white">Hex: #9aa5b1</div>

#### Border Colors

<div style="background-color: #d7dae6; width: 150px; padding: 10px; color: black">Hex: #d7dae6</div>
<div style="background-color: #e4e7eb; width: 150px; padding: 10px; color: black">Hex: #e4e7eb</div>

#### Background Colors

<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #f1f5f8; width: 150px; padding: 10px; color: black">Hex: #f1f5f8</div>


#### Font-families

- Roboto

