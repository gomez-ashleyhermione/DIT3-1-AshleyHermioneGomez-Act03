Reflection Questions:

-What design choices did you make (colors, fonts, layout)?

Colors
I'll be honest, I just used the colors that were given in the step-by-step guide. 
I kept the default purple colors that came with Android Studio and added the blue (#2196F3) for the button because it looked nice. 
The gray_light (#F5F5F5) for the background was suggested and it does make the screen less harsh than pure white. 
I used gray_dark (#757575) for the bio text to make it look less important than the name.
I didn't really experiment much with different colors because I was more focused on getting the layout to work properly first.

Fonts & Layout
Following the instructions, I used 24sp for the name and 16sp for the bio. I chose ConstraintLayout because that's what was recommended in the guide.
To be honest, setting up the constraints was the hardest part and I had to keep adjusting them because things weren't centering properly at first.
I made sure to use sp for text and dp for spacing like the instructions said. The profile picture is 120dp which seemed like a good size and not too big, not too small.

Layout Structure
I followed the layout structure from the guide pretty closely. Profile picture at the top, centered. Then the name below it with 16dp margin.
The bio is below the name with 8dp spacing, and I made it span across the screen with 32dp margins on both sides so it doesn't touch the edges.
The edit button is at the bottom with 48dp margins on the sides. I added minHeight="48dp" to the button because the guide mentioned it's important for accessibility and making it easy to tap.

-How did you ensure the screen is user-friendly and accessible?

I added android:contentDescription for the profile image. Honestly, I didn't fully understand why until I read that it helps screen readers tell visually impaired users what the image is.
and the button has minHeight="48dp" which I learned is the minimum size for people to tap comfortably. I didn't know this before.
Also, I used dark text on light background. I didn't measure the exact contrast ratio but it looks readable to me.
I used sp units for text sizes so if someone has larger text settings on their phone, it will adjust. This was mentioned in the instructions.
When I tested it in landscape mode, everything stayed in place but it looked a bit squished. The ConstraintLayout kept things centered though.

-What would you improve if this were a real app?

If this were a real app, I would:

1. Make the edit button actually work - right now it doesn't do anything when you click it. I'd need to learn how to make it open an edit screen.
2. Let users upload a real profile picture - instead of just the placeholder icon. Not sure how to do this yet but it would be necessary.
3. Add dark mode - The guide mentioned values-night folder for dark mode. I didn't implement it because I was still struggling with the basic layout, but it would be cool to have.
4. Add more profile information - like email, phone number, or social media links. Right now it's pretty basic.
5. Make the layout look better in landscape - it works but it could be prettier. Maybe rearrange things differently when rotated.





