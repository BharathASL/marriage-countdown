# Marriage Countdown

A simple static website displaying a countdown to your wedding day, featuring a responsive design, customizable background, and real-time updates.

## Forming the URL

To access your customized countdown page, you can form the URL using the following format:

```
https://<your-username>.github.io/marriage-countdown/?couple=<CoupleName>&date=<EpochTimestamp>&background=<BackgroundImageURL>
```

### Parameters:
- **couple**: The names of the couple (e.g., `Bharath & Steffi`).
- **date**: The wedding date as an epoch timestamp (in milliseconds).
- **background**: The URL of the background image you want to use. Ensure this is a direct URL to an image file.

### Example:
``` 
https://bharathasl.github.io/marriage-countdown/?couple=Bharath%20%26%20Steffi&date=1717293600000&background=https://example.com/path/to/your/image.jpg
```

## Customizing the Background

To customize the background image:

1. **Clone or Fork the Repository:**
   - To clone, use:
     ```bash
     git clone https://github.com/<your-username>/marriage-countdown.git
     ```
   - To fork, click the "Fork" button on the top right of the repository page.

2. **Add Your Background Image:**
   - Upload your desired background image to the repository. You can do this by dragging and dropping the image file into your repository on GitHub or using the command line.
   - Ensure you get the direct URL for your image after uploading. This can usually be done by right-clicking on the image and selecting "Open image in new tab" or a similar option.

3. **Update the URL:**
   - Use the direct URL of your uploaded background image in the URL format provided above.

## Using the Couple and Date Parameters

- **Couple Parameter**: This should be URL-encoded. For example, use `%20` for spaces and `%26` for the ampersand (`&`).
- **Date Parameter**: The date should be in epoch timestamp format (milliseconds since January 1, 1970). You can convert your wedding date to an epoch timestamp using various online converters or programming languages.

### Example URL with Parameters:
```
https://bharathasl.github.io/marriage-countdown/?couple=Bharath%20%26%20Steffi&date=1717293600000&background=https://example.com/path/to/your/image.jpg
```

## Hosting Your Website

Once you have made your changes and added your background image, you can push your changes back to your GitHub repository to host your updated countdown page on GitHub Pages.

Enjoy counting down to your special day!
