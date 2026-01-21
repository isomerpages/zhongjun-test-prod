---
title: Test page
permalink: /test/
description: ""
variant: markdown
---
<style>

  

p {

font-family: 'Lato', sans-serif;

font-size: 16px;

line-height: 26px;

}

  

h1, h2, h3, h4, h5, h6, li {

font-family: 'Lato', sans-serif;

line-height: initial;

}

  

.col-1 {width: 8.33%;}

.col-2 {width: 16.66%;}

.col-3 {width: 25%;}

.col-4 {width: 33.33%;}

.col-5 {width: 41.66%;}

.col-6 {width: 50%;}

.col-7 {width: 58.33%;}

.col-8 {width: 66.66%;}

.col-9 {width: 75%;}

.col-10 {width: 83.33%;}

.col-11 {width: 91.66%;}

.col-12 {width: 100%;}

  

.videoframe {

position: relative;

padding-top: calc(1 / 1 \* 100%);

}

  

.videoframe iframe{

position: absolute;

top: 0;

left: 0;

width: 100%;

height: 100%;

}

  

.video-container {position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden; }

  

.video-container iframe, .video-container object, .video-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }

  

video\[poster\]{

width:100%;

object-fit: cover;

}

  

.slide-txt {font-size: 20px; color: #FFFFFF; font-weight: 600; padding: 10px 65px; margin-top: 0px; line-height: initial !important;}

  

.w-100 {max-width: 100% !important;}

  

@media only screen and (max-width: 767px) {

\[class\*="col-"\] {

width: 100%;

}

  

.slider--cover .slider\_\_inner {

height: 600px !important;

}

  

.slide-txt {font-size: 16px; color: #FFFFFF; font-weight: 600; padding: 10px 25px; margin-top: 0px; line-height: initial !important;}

}

  
  
  

.timeline {

border-left: 4px solid #cee2d7;

border-bottom-right-radius: 4px;

border-top-right-radius: 4px;

background: rgba(255, 255, 255, 0.03);

margin: 50px auto;

letter-spacing: 0.5px;

position: relative;

line-height: 1.4em;

font-size: 1.03em;

padding: 50px;

list-style: none;

text-align: left;

font-weight: 100;

  

}

.timeline h1,

.timeline h2,

.timeline h3 {

letter-spacing: 1.5px;

font-weight: 100;

font-size: 1.4em;

}

.timeline .event {

border-bottom: 1px dashed rgba(255, 255, 255, 0.1);

padding-bottom: 25px;

margin-bottom: 50px;

position: relative;

list-style: none;

}

.timeline .event:last-of-type {

padding-bottom: 0;

margin-bottom: 0;

border: none;

}

.timeline .event:before,

.timeline .event:after {

position: absolute;

display: block;

top: 0;

}

.timeline .event:before {

left: \-217.5px;

color: rgba(255, 255, 255, 0.4);

content: attr(data-date);

text-align: right;

font-weight: 100;

font-size: 0.9em;

min-width: 120px;

}

.timeline .event:after {

box-shadow: 0 0 0 4px #0c6c37;

left: \-57.85px;

background: #0c6c37;

border-radius: 50%;

height: 11px;

width: 11px;

content: "";

top: 5px;

}

  

.carousel, .carousel2 {

position: relative;

margin-top: 26px;

}

  

.carousel-inner, .carousel-inner2 {

position: relative;

overflow: hidden;

width: 100%;

}

  

.carousel-open:checked + .carousel-item, .carousel-open:checked + .carousel-item2 {

position: static;

opacity: 100;

}

  

.carousel-item, .carousel-item2 {

position: absolute;

opacity: 0;

\-webkit-transition: opacity 0.6s ease-out;

transition: opacity 0.6s ease-out;

}

  

.carousel-item img, .carousel-item2 img {

display: block;

height: auto;

max-width: 100%;

}

  

.carousel-control, .carousel-control2 {

background: rgba(0, 0, 0, 0.28);

border-radius: 50%;

color: #fff;

cursor: pointer;

display: none;

font-size: 40px;

height: 40px;

line-height: 35px;

position: absolute;

top: 50%;

\-webkit-transform: translate(0, \-50%);

cursor: pointer;

\-ms-transform: translate(0, \-50%);

transform: translate(0, \-50%);

text-align: center;

width: 40px;

z-index: 10;

}

  

.carousel-control.prev, .carousel-control2.prev {

left: 2%;

}

  

.carousel-control.next, .carousel-control2.next {

right: 2%;

}

  

.carousel-control:hover, .carousel-control2:hover {

background: rgba(0, 0, 0, 0.8);

color: #aaaaaa;

}

  

#carousel-1:checked ~ .control-1,

#carousel-2:checked ~ .control-2,

#carousel-3:checked ~ .control-3,

#carousel-12:checked ~ .control-1,

#carousel-22:checked ~ .control-2,

#carousel-32:checked ~ .control-3,

#carousel-13:checked ~ .control-1,

#carousel-23:checked ~ .control-2,

#carousel-33:checked ~ .control-3 {

display: block;

}

  

.carousel-indicators {

list-style: none;

margin: 0;

padding: 0;

position: absolute;

bottom: 2%;

left: 0;

right: 0;

text-align: center;

z-index: 10;

display: none;

}

  

.carousel-indicators li {

display: inline-block;

margin: 0 5px;

}

  

.carousel-bullet {

color: #fff;

cursor: pointer;

display: block;

font-size: 35px;

}

  

.carousel-bullet:hover {

color: #aaaaaa;

}

  

#carousel-1:checked ~ .control-1 ~ .carousel-indicators li:nth-child(1) .carousel-bullet,

#carousel-2:checked ~ .control-2 ~ .carousel-indicators li:nth-child(2) .carousel-bullet,

#carousel-3:checked ~ .control-3 ~ .carousel-indicators li:nth-child(3) .carousel-bullet {

color: #428bca;

}

  

.slider {

position: relative;

max-width: 100%;

max-height: 100%;

margin: 0 auto;

}

.slider:hover .slider\_\_radiobox-label--prev,

.slider:hover .slider\_\_radiobox-label--next {

opacity: 1;

}

.slider:hover .slider\_\_radiobox-label--prev {

left: 2%;

}

.slider:hover .slider\_\_radiobox-label--next {

right: 2%;

}

.slider--cover {

width: 100vw;

}

.slider--fixed {

width: 600px;

height: 400px;

}

.slider--proportional {

width: 100%;

height: auto;

}

  

.slider\_\_inner {

position: relative;

margin: 0 auto;

overflow: hidden;

background: #ddd;

}

.slider--cover .slider\_\_inner {

width: 100%;

height: 300px;

}

.slider--fixed .slider\_\_inner {

width: 100%;

height: 100%;

}

.slider--proportional .slider\_\_inner {

width: 100%;

height: 0;

}

.slider--proportional-4x3 .slider\_\_inner {

padding-top: 75%;

}

.slider--proportional-5x4 .slider\_\_inner {

padding-top: 80%;

}

.slider--proportional-16x9 .slider\_\_inner {

padding-top: 56.25%;

}

  

.slider\_\_slides {

position: absolute;

top: 0;

right: 0;

bottom: 0;

left: 0;

z-index: 1;

width: 400%;

height: 100%;

overflow-y: hidden;

transition: margin-left 0.4s;

}

  

.slider\_\_slide {

display: block;

float: left;

position: relative;

width: 25%;

height: 100%;

}

.slider\_\_slide img {

width: 100%;

height: 100%;

\-o-object-fit: cover;

object-fit: cover;

}

  

.slider\_\_radiobox-label {

display: block;

position: absolute;

z-index: 2;

cursor: pointer;

}

.slider\_\_radiobox-label--item {

bottom: 6%;

left: 50%;

transform: translateX(\-50%);

padding: 6px;

border-radius: 50%;

background: white;

opacity: 0.3;

transition: opacity 0.2s;

}

.slider\_\_radiobox-label--item:hover {

opacity: 0.5;

}

.slider\_\_radiobox-label--item-1 {

margin-left: \-36px;

}

.slider\_\_radiobox-label--item-2 {

margin-left: \-12px;

}

.slider\_\_radiobox-label--item-3 {

margin-left: 12px;

}

.slider\_\_radiobox-label--item-4 {

margin-left: 36px;

}

.slider\_\_radiobox-label--prev, .slider\_\_radiobox-label--next {

display: none;

top: 50%;

transform: translateY(\-50%);

height: 0;

border: 10px solid #FFF;

border-top-color: transparent;

border-bottom-color: transparent;

opacity: 0;

transition: left 0.2s, right 0.2s, opacity 0.2s;

}

.slider\_\_radiobox-label--prev {

left: \-2%;

border-left: 0;

border-right-width: 17px;

}

.slider\_\_radiobox-label--next {

right: \-2%;

border-right: 0;

border-left-width: 17px;

}

  

.slider\_\_radiobox {

display: none;

}

.slider\_\_radiobox--1:checked ~ .slider\_\_slides {

margin-left: 0;

}

.slider\_\_radiobox--2:checked ~ .slider\_\_slides {

margin-left: \-100%;

}

.slider\_\_radiobox--3:checked ~ .slider\_\_slides {

margin-left: \-200%;

}

.slider\_\_radiobox--4:checked ~ .slider\_\_slides {

margin-left: \-300%;

}

.slider\_\_radiobox--1:checked + .slider\_\_radiobox-label--item-1, .slider\_\_radiobox--2:checked + .slider\_\_radiobox-label--item-2, .slider\_\_radiobox--3:checked + .slider\_\_radiobox-label--item-3, .slider\_\_radiobox--4:checked + .slider\_\_radiobox-label--item-4 {

opacity: 1;

}

.slider\_\_radiobox--1:checked ~ .slider\_\_radiobox-label--prev-4, .slider\_\_radiobox--1:checked ~ .slider\_\_radiobox-label--next-2, .slider\_\_radiobox--2:checked ~ .slider\_\_radiobox-label--prev-1, .slider\_\_radiobox--2:checked ~ .slider\_\_radiobox-label--next-3, .slider\_\_radiobox--3:checked ~ .slider\_\_radiobox-label--prev-2, .slider\_\_radiobox--3:checked ~ .slider\_\_radiobox-label--next-4, .slider\_\_radiobox--4:checked ~ .slider\_\_radiobox-label--prev-3, .slider\_\_radiobox--4:checked ~ .slider\_\_radiobox-label--next-1 {

display: block;

}

  

.rounded20 {

\-webkit-border-radius: 20px;

\-moz-border-radius: 20px;

border-radius: 20px;

}

  

.instagram-media {margin: auto !important;}

  

/\*\* LIGHTBOX MARKUP \*\*/

  

.lightbox {

/\* Default to hidden \*/

display: none;

  

/\* Overlay entire screen \*/

position: fixed;

z-index: 999;

top: 0;

left: 0;

right: 0;

bottom: 0;

/\* A bit of padding around image \*/

padding: 1em;

  

/\* Translucent background \*/

background: rgba(0, 0, 0, 0.8);

}

  

/\* Unhide the lightbox when it's the target \*/

.lightbox:target {

display: block;

}

  

.lightbox span {

/\* Full width and height \*/

display: block;

width: 80%;

height: 80%;

margin: auto;

/\* Size and position background image \*/

background-position: center;

background-repeat: no-repeat;

background-size: contain;

}
	
	</style>


<article style="max-width: 800px; width: 100%; margin: auto;">

<div style="width: 100%;">
  <a href="https://northwest.cdc.gov.sg/cohesion/january-2026/at-a-glance/">
    <img style="width: 100%; max-width: 100px; position: relative; float: left;" alt="North West Cohesion" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

	
<div style="width: 100%;">
  <img style="width: 100%;" src="https://northwest.cdc.gov.sg/images/Cohesion/January%202024/healthy_communities.png">
  <img style="width: 100%;" src="/images/Cohesion/Jan%202026/title_meet_fitnessx.jpg">
</div>
	
	
<div style="padding: 10px 0px 15px;">
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Start the year strong! Challenge yourself or try something fresh, and be inspired by the passionate instructors of our North West FitnessX Club classes. Take your pick from Zumba and K-pop Fitness to Fight-Do and High Intensity Interval Training (HIIT) and start your journey towards a stronger and fitter you!</p>
</div>
	
	
<div style="padding: 10px 0px 0px;">
  <p style="font-size: 20px; font-weight: bold; text-align: left; color: #F96B8D; margin: 0px 0px;"><b>#KopiTalk with North West FitnessX Club Instructors </b>
  </p> 
</div>
<div class="" style="max-width: 100%; padding: 25px 0px 0px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/Jan%202026/zumba_01.jpg">
</div>

</article>