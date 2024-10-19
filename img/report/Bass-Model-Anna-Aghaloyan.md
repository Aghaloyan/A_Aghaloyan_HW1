This paper focuses on the KIA EV6, one of TIME’s best inventions of
2023. It will explore the vehicle’s predecessor in innovation, apply the
Bass Diffusion Model to estimate its adoption, and forecast the number
of global users.

Although electric vehicles are generally expensive, KIA’s EV6 GT—named
the 2023 World Performance Car at the World Car Awards—stands out as an
affordable alternative, costing nearly half of what other EVs do without
compromising on performance. The EV6 GT accelerates from 0 to 100 km/h
in just 3.4 seconds, reaches a top speed of 260 kph, and even includes a
“drift mode” (TIME, 2023).

Kia’s EV6 GT encapsulates the brand’s philosophy, which centers around
the idea that movement drives human progress. It seeks to empower people
to explore new destinations, form meaningful connections, and embrace
fresh experiences. Kia aims to inspire its customers by offering
innovative products, immersive vehicle interiors, and services that free
up time for personal pursuits (TIME, 2023).

A comparable past innovation is Tesla’s electric vehicle series. Both
the KIA EV6 GT and Tesla models represent a strong commitment to
electric mobility, offering environmentally friendly alternatives to
gasoline-powered vehicles. These brands focus on sustainability,
integrating advanced technology to enhance performance, efficiency, and
the overall driving experience. They also share sleek, futuristic
designs that reflect a modern approach to vehicle aesthetics. Moreover,
both the KIA EV6 GT and Tesla aim to deliver a premium driving
experience, offering responsive handling, cutting-edge safety features,
and luxurious interiors. Together, they play a crucial role in the
ongoing shift toward more sustainable transportation solutions.

For the analysis of look-alike innovation, sales data from 2014 to 2023,
obtained from Statista, will be used for comparison and Bass Model
diffusion estimations.

![](Bass-Model-Anna-Aghaloyan_files/figure-markdown_strict/unnamed-chunk-3-1.png)
The graph illustrates Tesla’s global electric vehicle sales from 2016 to
2023, measured in thousands of units. The trend shows a consistent and
significant increase in sales year-over-year, with a particularly sharp
rise starting in 2021. In 2016, Tesla sold approximately 76,000 units,
and by 2023, this number had surged to over 1.8 million units,
showcasing Tesla’s growing dominance in the electric vehicle market. The
steep acceleration in sales from 2021 onwards reflects both the
increasing consumer demand for electric vehicles and Tesla’s expanding
production capacity.

![](Bass-Model-Anna-Aghaloyan_files/figure-markdown_strict/unnamed-chunk-4-1.png)

    ## Call: ( Standard Bass Model )
    ## 
    ##   BM(series = tesla$`Tesla sales in 1000 units`)
    ## 
    ## Residuals:
    ##     Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
    ## -37.390  -6.208   2.357  -0.153  10.508  30.796 
    ## 
    ## Coefficients:
    ##        Estimate    Std.Error        Lower        Upper  p-value    
    ## m 1.806735e+04 2.437149e+03 1.329062e+04 2.284407e+04 7.03e-04 ***
    ## p 3.115310e-03 2.696729e-04 2.586760e-03 3.643859e-03 8.53e-05 ***
    ## q 5.341205e-01 1.752740e-02 4.997675e-01 5.684736e-01 7.14e-07 ***
    ## ---
    ##  Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ##  Residual standard error  24.73652  on  5  degrees of freedom
    ##  Multiple R-squared:   0.999909  Residual sum of squares:  3059.478

ased on the summary of the model, the estimated values for the
parameters are as follows: the innovation rate p is approximately
0.003115, the imitation rate, q is approximately 0.534121, and the
market potential m is approximately 18067.35. These estimates indicate a
relatively low innovation rate and a higher imitation rate, suggesting
that while initial adoption may be slow, subsequent uptake through
imitation is likely to be significant. The market potential reflects a
substantial opportunity for growth in sales, reinforcing the potential
for widespread acceptance of the innovation.

    ## bass model
    ## 
    ## Parameters:
    ##                                 Estimate p-value
    ## p - Coefficient of innovation     0.0014      NA
    ## q - Coefficient of imitation      0.4642      NA
    ## m - Market potential          49479.7794      NA
    ## 
    ## sigma: 54.8096

We have almost the same values as for Method 1. I will choose the
parameters from the first method.
![](Bass-Model-Anna-Aghaloyan_files/figure-markdown_strict/unnamed-chunk-6-1.png)

## Sources 

*The product*

<https://time.com/collection/best-inventions-2023/6326978/kia-ev6-gt/>

*The look-like product*

<https://www.statista.com/statistics/502208/tesla-quarterly-vehicle-deliveries/>
