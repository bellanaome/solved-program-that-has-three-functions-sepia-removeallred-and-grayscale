Download Link: https://assignmentchef.com/product/solved-program-that-has-three-functions-sepia-remove_all_red-and-gray_scale
<br>
<ol>

 <li>Write a program that has three functions: sepia(), remove_all_red(), and gray_scale().</li>

</ol>




Sepia Tone images are those brownish colored images that may remind you of times past. The formula for creating a sepia tone is as follows:




newR = (R × 0.393 + G × 0.769 + B × 0.189)

newG = (R × 0.349 + G × 0.686 + B × 0.168)

newB = (R × 0.272 + G × 0.534 + B × 0.131)




Red removal from an image:




Simply set the R component to 0.




Gray scale conversion:




newR = (R × 0.289 + G × 0.587 + B × 0.114)

newG = (R × 0.289 + G × 0.587 + B × 0.114)

newB = (R × 0.289 + G × 0.587 + B × 0.114)







<em> </em>

<em>Hint:</em> Remember that rgb values must be integers between 0 and 255.

You can get each pixel by using p = img.getPixel(col, row)

Components of each pixel can be retrieved by p.getRed(), p.getGreen(), p.getBlue()




<table width="576">

 <tbody>

  <tr>

   <td width="576">#Starter code<strong>import</strong> imageimg = image.Image(“sample.jpg”)newimg = image.EmptyImage(img.getWidth(), img.getHeight())win = image.ImageWin()img.draw(win)win.exitonclick() </td>

  </tr>

 </tbody>

</table>








