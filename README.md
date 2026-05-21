# GRAM_MINI

  

*ALPHA VERSION, NOT MEANT FOR PRODUCTION YET.

  

# Introduction

  

**GRAM Mini** is a fork of the [GRAM Slim](https://github.com/GRAMCTRL/GRAM-SLIM), a low profile 21-button controller designed for Smash and FGC games. The GRAM MINI retains the same 21-button layout and firmware compatibility as the GRAM Slim, while downsizing the PCB and case design around a smaller, more compact form factor. This project is fully open-source and is intended to be very easy and staight-foward to build .

  

**This is a community fork and not an official GRAM product. If you would like to support the original designers, consider joining the official [GRAM Digital Controllers Discord server](https://discord.com/invite/6TuHw2r2X4) to recieve updates on the GRAMCTRL teams's new projects.**

  

![GRAM MINI](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)

  

## Included Files

  

Included in this repo are all the files needed to build a GRAM MINI:

  

-  **Gerber files** for PCB fabrication

-  **bom.csv and positions.csv** — for PCBA fabrication

-  **STL/STEP files** for 3D printing the enclosure

-  **KiCad source files** for the PCB design

-  **Case/shell design files** -for the enclosure design

  
  

*Note: Firmware is not included in this repository. This controller runs [Haybox-GRAM]([https://github.com/JonnyHaystack/haybox](https://github.com/GRAMCTRL/HayBox-GRAM)). Refer to the Haybox-GRAM documentation for flashing and configuration.*

  

## Thanks & Acknowledgements

  

There are several people who made this project possible, either directly or indirectly.

  

- [GRAMCTRL](https://github.com/GRAMCTRL), that designed the original GRAM Slim that this fork is based on.

- [CarVac](https://github.com/JonnyHaystack), who helped me with designing the GRAM MINI's PCB*

- [TBox](https://linktr.ee/tb0x), who jump-started my interest in making this project.

  
  

# Ordering & Customization Guide

  

For a full walkthrough on ordering PCBs and enclosure, refer to the original GRAM Slim documentation:


Make sure to use the Gerber and position.csv files from **this repository** when placing your order, as the PCB dimensions and component placement differ from the original GRAM Slim.
  

[GRAM Slim — Ordering & Customization Guide](https://github.com/GRAMCTRL/GRAM-SLIM#ordering--customization-guide)

  


# Build Guide

  

## Video Guide

  

**[Video build guide coming soon](#)**

*Unfortunatley the video guide is not available at the moment, but the link will be updated as soon as it will be uploaded*

  

## Soldering

  

Only two components require manual soldering. All other components will be soldered by JLCPCB if you select PCBA.

  

Before you start, confirm you have the following components:

  

-  **[Kailh Choc 1350 hotswap sockets](https://a.aliexpress.com/_EzR1QHC)** × 21

-  **[USBC connector](https://a.aliexpress.com/_EzR1QHC)** × 1 *(only if you did **not** select the Standard PCBA option when ordering)*

  

### Kailh Choc Hotswap Sockets

  

Solder one socket per button footprint (21 total) on the underside of the PCB.

  


![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)
  

Apply a small amount of solder to one pad first, then hold the socket in place and reflow to tack it before soldering the second pad. A good joint will be shiny and fully cover the socket tab.

  

### USB-C Connector *(skip if ordered via PCBA)*

  

The USB-C connector uses SMD pads as well as through-hole pins and requires care to avoid damaging the pads.

For this reason (unless you are very experienced), I suggest soldering the SMD pads using either a ***Hot plate*** or a ***Hot air gun*** and using ***Solder paste***

  -[**hot air gun video guide**](https://www.youtube.com/watch?v=VL5mSLma4D4)
  -[**hot plate video guide**](#)

First of all take your  USBC module and remove the back cover by loosening the side latches and wiggling the back cover as shown in the pictures. this is NOT necessary but recommended to inspect the pins once they have been soldered.
![LOOSEN SIDE LATCHES](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)
![WIGGLE BACK FLAP](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)
  
After removing the back flap, place a thin layer of solder paste on the SMD pads and place the USBC connector on the board
![SOLDER PASTE](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)
![USBC CONNECTOR ON TOP OF SOLDER PASTE](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)

Using your soldering method of choiche, solder the SMD pads with the USBC pins
![SOLDERED PADS](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)
***-DO NOT WORRY IF THE PIN GROUPS THAT ARE HIGHLIGHTED ARE BRIDGING, AS PINS  AND  ARE UNROUTED-***

Flip the board and using a soldering iron with a CONTROLLABLE TEMPERATURE, fill the through-holes with solder. After you are done use a multimeter to check for bridging between the pins (or just give it an eye test).
![SOLDERED THROUGH-HOLES](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)
## Assembly

  

**Step 1 — Print or source the case**

  

Using the STL/STEP files in the repo, print or order your shell components. Check the fit with your PCB before proceeding.



**Step 2 — Install the switches**

  

Place the first top plate on top of the PCB and, while being careful not to bend any pins, orient the switch so as to have the two pins alligned to the socket's holes and press it down firmly into the PCB.
***-MAKE SURE THAT THE POSITION AND NUMBER OF. SWITCHES
YOU INSTALLED CORRESPONDS TO THE ONE OF YOUR PREFERRED TOP PLATE-***

  

![SWITCH ORIENTATION](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)
![SWITCH BEING INSTALLED](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)
  -NOTE: this is the perfect time to flash your controller and check if every button works

**Step 3 — Close the enclosure**

Place the topmost plate and the two bottom plates as shown in the image, then insert your  4x 11mm Chicago screws in the designated holes while making sure the flat side is facing upwards and tighten the screws.

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)

After doing that, install your keycaps by alligning the cross on the keycaps with the cross on you switches and pressing down firmly.

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)
  

**Step 6 — Final step**

  

Enjoy your new controller =)

  

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAP4AAADGCAMAAADFYc2jAAAAKlBMVEXQ0NDw8PDNzc3e3t7X19fs7Ozu7u7U1NTS0tLd3d3Z2dnl5eXi4uLn5+djo+YlAAADyUlEQVR4nO2dCYKjIBBF27gbvf91JwYnCcoiylr13wn4XQ8Kwdh/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACgbPpprOtx6h+pB5KAfm676k3X1n3q0URmelYSM6c/wDB31Y62Tj2oaAzPffiVJ5MloG9V6atqGVKPLAqLOv2r/hzyz7r0VTWmHlt4psOq9wP59X/Qqv/WP/XwQjOZ0lddk3p8gVH2vC9z6vEFxpy+WmjP/sYSn7j9oyV+NaUeYVAsU594639Y45N+8nkYu/4K7aWfd/VNG34B7aXPvOl7QbvxDZb0Le1tj/5hX0B75bPue2hPff1J1+Y++fMeY/mpF9983sHhsLfXq0982RfoTvta2j3/w6Rc/njUfqVRzH/i5zwSQ70L343kW57EULefJaBbaD/nKRmmen4uy3OumSx5R4YXqccAAAAAAAAAAAAAAPKmYXt6ttJ0XC5MVDQtpyuTPeIKjfjboVqajteFoUzzuT7kmP/38rRjN//lq3Nu9W92Lw7wyt8cXhvg5L/qpRE+/W9vPi//j+Zv+Vn4r/9xJIf8avO5+K8zn0d+c3rq/ht/FE2+/qZ5Tz+/zXza/tvNF9Dc/50xn67/58yn6r/61XAu+c+bT9F/F/OLyN+4vNntnj5z/yeXnzGe7XjF1P+9kJ3N7zrvs8+/BapP/Zjtivlb/jz9/3zU5Ez9r5mfcf1/AtnzXzU/2/xSIJv/183f8ufm/+5zPub+dzd9dvkPU9nk/z3zt/w5+a/Yus9a/+/XPrP8vaqcus8X+Umfkf+aJqb2/07H2+XPo/7ah1ZVfh/zPqv8hkDH/ufL/C1/ev+NH7Db9z9/5m/5U9ffEkj236f5WeS3yvzrv1/zt/wp/dd/xeObP2j6pPlPTeX//vs3f8ufyv+Tx7Ri/xem9gnzK/d6KsZHyPSJvhRl/XLdlzmY+YIE9Xe6oJgD1n4lev6w5XQm8vqfWfrI+X1vXj0Q0f+Qy/hlotX/dMeLS6T8GZoviOK/25V8VCLkz9R8QfD9n8NeLwWB65+x+YKg+bPb7RwJuP4XkD5g/mw7nkwg/7Pc66kIUv+sO55MgPyFmC/w7n/2HU/Gc/6CzBd43f8V0fFkPNa/MPMF3vIXWPsVT+t/oek95S+q48l48L+YvZ6K2/UvruPJ3MxfsPmCW/4X2fFkbuQv3HzB5f1fsR1P5uL8J2C+4JL/RXc8mQv1J2K+wDl/8R1PxtF/QuYLnOpPouPJOOQnZr7gvP9TTRH6/yoQAAAAAAAAAAAAGw/W/KU+hUrLPxqeOVrdjftAAAAAAElFTkSuQmCC)

  

---

  

*This project is licensed under [GPL-3.0](./LICENSE). Based on the [GRAM Slim](https://github.com/GRAMCTRL/GRAM-SLIM) by GRAMCTRL, also licensed under GPL-3.0.*
