{
  "name" : "card-footer",
  "type" : "Component",
  "category": “Layout”,
  "version" : "1.0.0",
  "averageRating" : 1,
  "description" : "This component contains the section anchored to the bottom of the card. And the       provided data will be written as the footer. It accepts string value “ ,
  "platformSupportVersion" : "4.0.0",
  "publisher" : "Ayush"

}



## Guide:
### Overview:
A card footer is a sub-container of card. In this we can give the information which will be displayed as a footer in the card.

##### Usage:
Card footer can be used where the data should be displayed as footer,at the bottom of any container. It can contain data such as string value ,logo or anything  inside it.
##### How to use
Drag and drop a card footer component where it can be used, basically it is used at the bottom that is below every components.
##### Example
**Display a card with a title, a image, a paragraph about that image and a card footer**
- Drag and drop a card component and provide the style and class for that.
- Drag and drop a card title inside the card and give the title=Tajmahal
- Drag and drop a paragraph inside the card component below the card-title and provide the path of the image in imgSrc attribute that is stored in the system so if the image is in asset folder then the path can be (asset\android\taj.jpg) and,the image taj.jpg will be displayed on the screen.
- Now,drag and drop a paragraph component inside card below the card-image and in text attribute provide some information about the image.
- Now drag and drop a card footer inside the card below all components and drag a paragraph component inside the footer component and provide some text that can be displayed as a footer on the screen.
### Associated Attributes:
- **Style**-accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element. An inline CSS uses the style attribute of an HTML element.
(eg. color:blue).

- **Class**- it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=toolbar)



### Support 
- **Devices:** Android, iOS
- **Browsers**:  Latest version of all modern browsers
- **Dependencies version:** 
 Angular CLI version: 5.0.0 + 
 Cordova version: 7.1.0 +










