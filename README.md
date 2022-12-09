# Arduino
## Final Project weekly diary
“Xianbei” weekly diary
## Week 6 
This week I determined the theme I want to do and the macro realistic way.
My work is called "Xianbei". 

This is the name of my cat. She is a British Shorthair cat.I have taken her home since she was born and she is now three years old.After I arrived in the UK, the Xianbei had to stay in Beijing, and I missed her very much.

<img width="598" alt="image" src="https://user-images.githubusercontent.com/76156342/206602184-ac4c0b33-0aab-4fa5-a758-9228f6263d57.png">

I want to make a device that allows me to see and hear Xianbei in London. 

First, I thought of making a 3D model that would allow me to touch the Xianbei. However, in terms of material selection, it is impossible to achieve a real cat effect, and at the same time, the cat cannot move smoothly.

One day, I saw a gif of a cat. I think, if you want the cat to move smoothly, maybe you can use cartoons to achieve it.

I thought that I could make a turntable, draw a few coherent movements of cats, and use the motor to drive the turntable to make the animation move.

<img width="746" alt="image" src="https://user-images.githubusercontent.com/76156342/206614047-2e58ddd4-46bd-4c68-937b-b8c59d848f48.png">

What kind of trigger is used to turn it?I wanted to do an animation of cats playing, so it occurred to me that I could use a cat toy to trigger the rotation of the mechanism.That is, when the user picks up the cat toy to play with the cat, the device starts to rotate, and the user can see the kitten playing all the time.

<img width="764" alt="image" src="https://user-images.githubusercontent.com/76156342/206614018-79aca9a7-422b-4482-8390-f2af543988b4.png">

At the same time, I think I can add a cat's meow.When the user passes by the device, the Xianbei will make a sound to attract the user's attention.After users are attracted, they will naturally pick up cat toys and play with Xianbei.

<img width="646" alt="image" src="https://user-images.githubusercontent.com/76156342/206613950-b74a127b-1f7c-49d2-857e-97074764aba0.png">

I determined my two inputs and two outputs this week.One is a pressure sensor and motor, and the other is an ultrasonic sensor and audio playback.

## Week 7

This week, I drew an animation of the cat based on the appearance of the Xianbei, and cut the animation by laser.

<img width="956" alt="image" src="https://user-images.githubusercontent.com/76156342/206602236-cb6f9e6e-be49-443d-8847-e85131c0dc4c.png">

![未命名作品 2](https://user-images.githubusercontent.com/76156342/206604418-67f5b79c-e8a3-402f-b62c-6f854ad6beee.gif)

<img width="516" alt="image" src="https://user-images.githubusercontent.com/76156342/206602277-9ec2d118-5703-4078-865f-b856632162ea.png">

Since I found that the pattern drawn on the acrylic plate is not very obvious, I thought to add a light to the previous turntable. That is to say, through pressure induction, not only to start the motor, but also to light up the LED lights.

This week I also downloaded the 3D model of the turntable, and printed the 3D model of the turntable using a 3D printer.

<img width="602" alt="image" src="https://user-images.githubusercontent.com/76156342/206602335-428039ef-31c5-4bb7-bf1a-dce8e106e7bf.png">

<img width="515" alt="image" src="https://user-images.githubusercontent.com/76156342/206602113-d3987a86-d43b-4116-8082-08539324b10d.png">

## Week 8

This week I started writing the code, linking and testing the circuit.

The first is the pressure sensor controlling the motor and LED lights.

At first, I wanted to use a tiny servo to drive the turntable. However, after testing, it was found that the power of the micro servo was too small to drive the heavy turntable.

<img width="511" alt="image" src="https://user-images.githubusercontent.com/76156342/206602477-627c0016-77e8-46ad-984f-bf6ce0a94509.png">

So, I decided to use a toy motor to drive the turntable.But using a toy motor also requires a driver, so I learned to use L298N.

<img width="596" alt="image" src="https://user-images.githubusercontent.com/76156342/206602571-9a0682b9-18e9-4fca-acc9-6a0701817cd0.png">

<img width="604" alt="image" src="https://user-images.githubusercontent.com/76156342/206602609-3e79586f-7d79-4f5d-bfe6-969d6a0df4a0.png">

I have completed the wiring diagram and code.

<img width="713" alt="image" src="https://user-images.githubusercontent.com/76156342/206602646-7f2a687c-9901-4e19-b3f1-cb2372d0270a.png">

<img width="473" alt="image" src="https://user-images.githubusercontent.com/76156342/206602695-f7a620c2-2d61-417e-a757-a6aca906690a.png">

<img width="477" alt="image" src="https://user-images.githubusercontent.com/76156342/206602728-3310feab-5d99-4d63-bb25-25720f915351.png">

And the test is successful.

<img width="638" alt="image" src="https://user-images.githubusercontent.com/76156342/206602787-bad6dd05-2401-4674-ba65-fd4185698e98.png">

<img width="673" alt="image" src="https://user-images.githubusercontent.com/76156342/206602832-be0ab4d2-c55e-4698-8d7e-7b974c24b17a.png">

The other part, the part that controls the sound playback through the ultrasonic sensor, also completes the circuit diagram and code.

I extracted the sound of Xianbei from the video, put it into the SD card, and read it through DFPlayer mini. When the user gets close to the device, the senbei can be heard.

<img width="847" alt="image" src="https://user-images.githubusercontent.com/76156342/206602906-d18adbf8-6ea5-4816-aa4b-4b87ef260f6c.png">

<img width="525" alt="image" src="https://user-images.githubusercontent.com/76156342/206602942-76fcd3ad-a402-4bb4-babc-093b92e3c6a3.png">

<img width="526" alt="image" src="https://user-images.githubusercontent.com/76156342/206602972-99431d24-8057-42f9-bbcd-8402b9535315.png">

<img width="524" alt="image" src="https://user-images.githubusercontent.com/76156342/206603041-1b231644-3119-4e2a-b5de-f1a828c85892.png">

Also tested.

<img width="672" alt="image" src="https://user-images.githubusercontent.com/76156342/206603100-b99d5b37-1691-42ed-8c05-1ea5f79e607e.png">


## Week 9

This week I did the final testing and assembly.

I used AI to make a base box to place the ultrasonic and horn and wiring.

<img width="581" alt="image" src="https://user-images.githubusercontent.com/76156342/206603235-58d0e593-76e9-49ec-a3d2-2783d8514275.png">

I placed the wiring in the box and assembled the turntable.

<img width="658" alt="image" src="https://user-images.githubusercontent.com/76156342/206603301-1f32b7b3-6c12-4717-840c-bf18d09bbd50.png">

<img width="660" alt="image" src="https://user-images.githubusercontent.com/76156342/206603369-13ee4bef-ae33-471a-8068-a124d524a6aa.png">

Attach the pressure sensor to the cat toy.

<img width="636" alt="image" src="https://user-images.githubusercontent.com/76156342/206603426-ed81c3c3-d781-4c3d-b3b3-d295bd5fe3e8.png">

Finally, finish the work and shoot the video.

<img width="677" alt="image" src="https://user-images.githubusercontent.com/76156342/206603489-0f1f68df-3587-4b0d-a80c-ca1f03ee0e3b.png">

<img width="673" alt="image" src="https://user-images.githubusercontent.com/76156342/206603525-da24af66-a1b3-45f3-bd66-fc0ac0f785d7.png">

<img width="671" alt="image" src="https://user-images.githubusercontent.com/76156342/206603572-8c286107-a2d4-438f-8800-3cf13483e6e7.png">

<img width="675" alt="image" src="https://user-images.githubusercontent.com/76156342/206603612-6b8aca3a-2a0d-48dd-8ae8-1505a0060685.png">

When the user gets close, they can hear the sound of Xianbei. Users can pick up the cat toy and watch the animation of Xianbei playing.

<img width="672" alt="image" src="https://user-images.githubusercontent.com/76156342/206603653-6dfa1542-0bbb-4534-b5dc-13cea76f1bd6.png">

<img width="673" alt="image" src="https://user-images.githubusercontent.com/76156342/206603691-8fa86fbc-889f-416c-bd67-a333d15f9feb.png">






