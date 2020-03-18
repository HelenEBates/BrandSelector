# BrandSelector
Lots of womens clothes shops have slightly different sizes. This programme explores how to make find which brands fit you.
Data from River Island, Topshop and Zara size guides for size 12 dresses where used in the CSV file. The first value is bust, then waist, then hips.
The first step was to read in the file then allow the user to enter their own values.
For a good fit the user entered values need to be lower than each value from the brand

Next steps include a method to see how close a users waist to hip ratio is to that of a particular brand. Thoughts below
 Are there any methods we can use which make use of ratios? https://insideoutstyleblog.com/2009/06/proportions-the-golden-mean-or-fibonacci-number.html would have to add garment length in

-          http://isntthatsew.org/flat-pattern-making-foundation/   Calculate your WHR by dividing your waist circumference by your hip circumference

-          Method – skirtFitting(double brandWaist, double brandHip, double userWaist, double userHip) {

o   brandWHR = brandWaist / brandHip

o   userWHR = userWaist / userHip

o   if

-          }

-          Zara size 12 is 0.72, for sixe 10 is 0.71

-          Next 74 / 99 size 12 = 0.74, size 10 0.747

-          Should use SQL as a database, simple one, and link into Java

-          Would be great to find an open data source, maybe kaggle? For the data

Blog post on why clothes don’t fit you

We often use our size measurements to find out which size to buy, however it doesn’t always result in clothes that fit, looking into how

Clothes are made, we are familiar with idea body shapes, and clothing can be made to work with these by looking at ratios, waist to hip is a common one.

from patterns you can see that darts are used to fit the waist and hips. These darts are basically triangle shapes cut out, and by changing the angle of the triangle

We can make the waist to hip ratio larger or smaller. There’s no reason that we couldn’t provide our measurements then design a programme to draft a dressmaking pattern which would fit us perfectly, by adapting the angles for example on the skirt darts.

https://www.nextdirect.com/help/en/AU/Section.aspx?ItemId=15229

could use a method to calculate the angle for darts, 4 darts, difference between waist and hip divided by 4

a ‘perfect’ waist to hip ratio is 0.7, comparing back to sizes guides this makes zara pretty much bang on the money for the golden mean waist to hip ratios, up to 0.8 is considered healthy

https://www.goldennumber.net/human-body/
