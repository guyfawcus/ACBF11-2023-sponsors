https://stackoverflow.com/a/21528510/3548784

unoconv --export Quality=100 Small\ Screens\ 2022\ v2.ppt sponsors.pdf

convert -density 400 Small\ Screens\ 2022\ v2.pdf[0-9] sponsor-%d.jpg

convert -density 400 Small\ Screens\ 2022\ v2.pdf[10-19] sponsor-%d.jpg

convert -density 400 Small\ Screens\ 2022\ v2.pdf[20-31] sponsor-%d.jpg
