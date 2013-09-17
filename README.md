City-Skyline
============
size(1000,800);
fill(0,0,0);
rect(0,600,1000,200);//floor
fill(0,0,0);
rect(10,500,100,250);//1st building
fill(0,0,0);
rect(120,300,150,300);//Sears bottom
fill(0,0,0);
rect(150,150,90,200);//Sears mid
stroke(255);
strokeWeight(2);//Sears vertical
line(125,305,125,600);
line(132,305,132,600);
line(139,305,139,600);
line(146,305,146,600);
line(265,305,265,600);
line(258,305,258,600);
line(251,305,251,600);
line(244,305,244,600);
strokeWeight(5);//Sears horizonatal
line(160,160,230,160);
line(160,175,230,175);
line(160,190,230,190);
line(160,205,230,205);
line(160,220,230,220);
line(160,235,230,235);
line(160,250,230,250);
line(160,280,230,280);
line(160,295,230,295);
line(160,310,230,310);
line(160,325,230,325);
line(160,340,230,340);
line(160,355,230,355);
line(160,370,230,370);
line(160,385,230,385);
line(160,400,230,400);
line(160,415,230,415);
line(160,430,230,430);
line(160,445,230,445);
line(160,460,230,460);
line(160,490,230,490);
line(160,505,230,505);
line(160,520,230,520);
line(160,535,230,535);
line(160,550,230,550);
line(160,565,230,565);
line(160,580,230,580);
line(160,595,230,595);
stroke(0);
strokeWeight(6);
line(175,40,175,85);//lft attenna top
strokeWeight(10);
line(175,85,175,150);//lft attenna botton
strokeWeight(6);
line(215,40,215,85);//rght attenna top
strokeWeight(10);
line(215,85,215,150);//rght attena botton
fill(0,0,0);
rect(580,300,140,300);//backgroun building
rect(590,285,120,50);//background top
stroke(255);
strokeWeight(8);
line(590,310,590,600);
line(610,310,610,600);
line(630,310,630,600);
line(650,310,650,600);
line(670,310,670,600);
line(690,310,690,600);
line(710,310,710,600);
stroke(0);
strokeWeight(0);
fill(0,0,0);
rect(270,550,200,250);//3rd building bottom
fill(0,0,0);
rect(290,530,180,250);//3rd building mid
fill(0,0,0);
rect(330,400,100,600);//3rd builing top
triangle(330,400,380,320,430,400);//3rd building roof
fill(0,0,0);
rect(480,510,300,110);
rect(500,480,150,220);
rect(630,420,80,280);
rect(730,360,100,250);
fill(0,0,0);
quad(840,600,860,270,980,270,1000,600);//John Hancock
strokeWeight(4);
line(890,170,890,220);//Hancock lft attenna top
line(950,170,950,220);//Hancocl rght attenna top
strokeWeight(8);
line(890,220,890,270);//Hancock attenna lft botton
line(950,220,950,270);//Hancock rght attenna botton
strokeWeight(7);
stroke(255);
line(920,270,981,340);
line(920,270,859,340);
line(981,340,920,410);
line(859,340,920,410);
line(920,410,982,480);
line(920,410,858,480);
line(982,480,920,550);
line(858,480,920,550);
line(920,550,983,620);
line(920,550,857,620);
save("cityskyline.jpeg");
