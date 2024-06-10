#### CODE (Displaying_X-ray_on_OpticaLegacyImage)

The code is useful to extract from a x-ray image the x-ray morphology contours and displaying then on the a n optical image e.g from Legacy Sky Survey Browser

The most important cells of the code are:

Cell n° 2: Here we read de x-ray file

Cell n° 5: Here we define three  functions:

        cut_xray_image: Cut the x-ray image giving a FOV which will be importat to zoom and cut the optic image
        
        points: This function works to plot point on the x-ray+opcti image
        
        scale_lines: This function works to draw a scale line on the image

Cell n° 6: We define the FOV

Cell n° 7: We cut the x-ray image and we save the FOV that we will use to cut the LS image

Cell n° 8: We download the legacy image using a size_pix, size_arcs (FOV) and a pixscale

Cell n° 9: We plot the x-ray contours on the optical image



#### X-ray image file (Abell2670_broad_flux.img)
It is saved in a zip file, it's very heavy

It is a x-ray image of Abell 2670 from Chandra for the cluster Abell 2670

X-ray morphology contours from Chandra
