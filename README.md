# Abstract
&emsp;&emsp;Our group has developed an **AR application** called "Sugar Rhythm", which focuses on the **traditional Chinese art** of **sugar painting** and is developed with Leap motion and Unity.This app integrates popularisation, observation and experience, and shows users the profoundness and fun of the traditional art of sugar painting from various angles, so as to promote the Chinese traditional art.
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/title.png?raw=true"/></div>  

# 1.Design Ideas
&emsp;&emsp;We chose sugar painting as the theme, through the data collection and discussion, we will be divided into three parts of the application, say, view, drawing, from science to observation to experience layer by layer, to bring users a better emotional padding and incremental effect, through the AR recognition display, leap motion gesture recognition and other technological means to convey the sugar painting not only has three good "good-looking, tasty, and fun," but also has a long history, contains a precious cultural imprint of the wisdom of the Chinese folk.
## 1.1 Project Innovation Points
The innovations are as follows：  
- **Theme creativity**, choosing sugar painting, which is a popular traditional food that is not often explored in depth, to explore and transform its cultural and experiential values;  
- **Content creativity**, AR technology is cleverly applied to all parts of the application, from display recognition to button interaction to gesture recognition painting interaction, diversifying and diversifying AR applications;  
- **UI creativity**, purely original UI design, set up original logos, labels, slogans, patterns, etc., unified style and colours, systematic and complete, and strive to create a UI design that is closer to the sugar paintings themselves and also has traditional Chinese cultural colours;  
- **Technical creativity**, the use of AR technology combined with leap motion gesture recognition to complete the functional module of interactive sugar painting, let the application "live", simulation of sugar painting stall scene, from the carousel to the sugar and then to the drawing, there are random and challenging, playability is high, interesting, interactive experience is good.
## 1.2 Overall Process Display
The overall usage process is as follows：  
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/mindmap.png?raw=true"/></div>  

## 1.3 UI Design
&emsp;&emsp;We designed the whole UI in Figma, 14 pages in total (12 pages of design, 1 page will be reused three times). During the design process, we used traditional Chinese colours to match the orange colour of the sugar paintings and designed our own Chinese graphic styles such as the Chinese Zodiac pattern, as well as a logo design for the theme of the project, and a slogan design.
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/UICOLOR.png?raw=true"/></div>  
<p align="center">(Choice of colour scheme and scrolling Zodiac graphic design)</p>
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/ui.png?raw=true"/></div>  
<p align="center">(overall UI design)</p>
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/lOGO.png?raw=true"/></div>  
<p align="center">(Logo icon and text design)</p>

## 1.4 Physical card production
&emsp;&emsp;We completed the registration of the database in the vuforia official website and uploaded the images that need to be scanned and recognised in preparation for the implementation of the scanned image display model
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/kapian.png?raw=true"/></div>  

## 1.5 Blender modelling
&emsp;&emsp;In this design, we made three models, including the sugar shop model, and two different shapes of sugar painting models, which are flat sugar painting and three-dimensional sugar painting.
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/MODEL_TANGPU.png?raw=true"/></div>  
&emsp;&emsp;The flat sugar painting model was chosen in the shape of ice dun-dun, which is the mascot of the Beijing Winter Olympics, and the three-dimensional sugar painting is a bouquet of roses, which jumps out of the common theme of the twelve Chinese zodiac signs, in the hope of bringing users an interesting and interesting AR viewing experience.
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/Model_tanghua.png?raw=true"/></div>  

# 2.Functional realisation
The specific functions are implemented as follows：
- Complete the UI implementation in unity according to the preliminary UI design and jump relationship diagram.
- Overall functional implementation of sugar painting：  
  ① Recognising the homemade card through AR, models of a sugar shop, a turntable, a sugar stove and a spoon appear (all of which are necessary for making sugar paintings).  
  ② The progress bar controls the progress of the furnace sugar  
  ③ Using a carousel to obtain random patterns to assist in sugar painting  
  ④ Hand-controlled Sugar Painting with Leap Motion,The specific gestures are as follows:
  
&emsp;&emsp;This section mainly uses gestures to simulate interactive effects and jump between drawing operations, for example, "enter the drawing view, i.e. top view (clench your fist)", "pinch the spoon, move only without drawing (thumb and index finger extended)", "start drawing the sugar painting, move your hand to draw the movement of your hand (five fingers open)", "clear the trajectory of the last drawing (index finger, middle finger and ring finger open at the same time)". "Starting to draw the sugar painting, moving the hand i.e. drawing the movement of the hand (five fingers spread out)", "Clear trajectory of the last stroke (index middle finger and ring finger spread out at the same time)", "Returning the spoon to the initial position (clenched fist )", "Return to the overall view of the sugar shop, i.e. the main view, representing the completion of the drawing (index and middle fingers open at the same time)".
The basic control chart for the gesture is shown below:
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/shoushi.png?raw=true"/></div>  

- Realisation of the overall sugar painting culture presentation：  
  ① Recognise images to play the introductory video  
  ② Recognise pictures showing 3D models  
  ③ Sugar painting history mind map display  

# 3.Presentation of final results
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/shiji.png?raw=true"/></div>  
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/shiji1.png?raw=true"/></div>  
<div align=center><img src="https://github.com/AlisonMeii/TangYun_ArProject/blob/main/Image/shiji2.png?raw=true"/></div>  
  
  
