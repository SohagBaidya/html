# html
Html sp3

 
 ​<!DOCTYPE html​> 
 ​<​html​ ​lang​="​en​" ​dir​="​ltr​"​> 
 ​   ​<​head​> 
 ​      ​<​meta​ ​charset​="​utf-8​"​> 
 ​      ​<​title​>​Popup Login Form Design | CodingNepal​</​title​> 
 ​      ​<​link​ ​rel​="​stylesheet​" ​href​="​style.css​"​> 
 ​      ​<​link​ ​rel​="​stylesheet​" ​href​="​https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css​"/> 
 ​      ​<​style​> 
 ​          ​@import​ ​url​(​'https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap'​); 
 ​*​{ 
 ​  ​margin​:​ ​0​; 
 ​  ​padding​:​ ​0​; 
 ​  ​outline​:​ none; 
 ​  ​box-sizing​:​ border-box; 
 ​  ​font-family​:​ ​'Poppins'​,​ sans-serif; 
 ​} 
 ​body​{ 
 ​  ​height​:​ ​100​%​; 
 ​  ​width​:​ ​100​%​; 
 ​   
 ​} 
  
 ​img​{  
 ​    ​width​:​ ​100​%​; 
  
 ​} 
 ​.​show-btn​{ 
 ​  ​background​:​ ​#​fff​; 
 ​  ​padding​:​ ​10​px​ ​20​px​; 
 ​  ​font-size​:​ ​20​px​; 
 ​  ​font-weight​:​ ​500​; 
 ​  ​color​:​ ​#​3498db​; 
 ​  ​cursor​:​ pointer; 
 ​  ​box-shadow​:​ ​0​px​ ​0​px​ ​10​px​ ​rgba​(​0​,​0​,​0​,​0.1​); 
 ​} 
 ​.​show-btn​,​ .​container​{ 
 ​  ​position​:​ absolute; 
 ​  ​top​:​ ​50​%​; 
 ​  ​left​:​ ​50​%​; 
 ​  ​transform​:​ ​translate​(​-50​%​,​ ​-50​%​); 
 ​} 
  
 ​input​[​type​=​"checkbox"​]{ 
 ​  ​display​:​ none; 
 ​} 
 ​.​container​{ 
 ​  ​display​:​ none; 
 ​  ​background​:​ ​#​fff​; 
 ​  ​width​:​ ​410​px​; 
 ​  ​padding​:​ ​30​px​; 
 ​  ​box-shadow​:​ ​0​ ​0​ ​8​px​ ​rgba​(​0​,​0​,​0​,​0.1​); 
 ​} 
 ​#​show​:​checked​ ​~​ .​container​{ 
 ​  ​display​:​ block; 
 ​} 
 ​.​container​ .​close-btn​{ 
 ​  ​position​:​ absolute; 
 ​  ​right​:​ ​20​px​; 
 ​  ​top​:​ ​15​px​; 
 ​  ​font-size​:​ ​18​px​; 
 ​  ​cursor​:​ pointer; 
 ​} 
 ​.​container​ .​close-btn​:​hover​{ 
 ​  ​color​:​ ​#​3498db​; 
 ​} 
 ​.​container​ .​text​{ 
 ​  ​font-size​:​ ​35​px​; 
 ​  ​font-weight​:​ ​600​; 
 ​  ​text-align​:​ center; 
 ​} 
 ​.​container​ ​form​{ 
 ​  ​margin-top​:​ ​-20​px​; 
 ​} 
 ​.​container​ ​form​ .​data​{ 
 ​  ​height​:​ ​45​px​; 
 ​  ​width​:​ ​100​%​; 
 ​  ​margin​:​ ​40​px​ ​0​; 
 ​} 
 ​form​ .​data​ ​label​{ 
 ​  ​font-size​:​ ​18​px​; 
 ​} 
 ​form​ .​data​ ​input​{ 
 ​  ​height​:​ ​100​%​; 
 ​  ​width​:​ ​100​%​; 
 ​  ​padding-left​:​ ​10​px​; 
 ​  ​font-size​:​ ​17​px​; 
 ​  ​border​:​ ​1​px​ solid silver; 
 ​} 
 ​form​ .​data​ ​input​:​focus​{ 
 ​  ​border-color​:​ ​#​3498db​; 
 ​  ​border-bottom-width​:​ ​2​px​; 
 ​} 
 ​form​ .​forgot-pass​{ 
 ​  ​margin-top​:​ ​-8​px​; 
 ​} 
 ​form​ .​forgot-pass​ ​a​{ 
 ​  ​color​:​ ​#​3498db​; 
 ​  ​text-decoration​:​ none; 
 ​} 
 ​form​ .​forgot-pass​ ​a​:​hover​{ 
 ​  ​text-decoration​:​ underline; 
 ​} 
 ​form​ .​btn​{ 
 ​  ​margin​:​ ​30​px​ ​0​; 
 ​  ​height​:​ ​45​px​; 
 ​  ​width​:​ ​100​%​; 
 ​  ​position​:​ relative; 
 ​  ​overflow​:​ hidden; 
 ​} 
 ​form​ .​btn​ .​inner​{ 
 ​  ​height​:​ ​100​%​; 
 ​  ​width​:​ ​300​%​; 
 ​  ​position​:​ absolute; 
 ​  ​left​:​ ​-100​%​; 
 ​  ​z-index​:​ ​-1​; 
 ​  ​background​:​ ​-webkit-linear-gradient​(right​,​ ​#​56d8e4​,​ ​#​9f01ea​,​ ​#​56d8e4​,​ ​#​9f01ea​); 
 ​  ​transition​:​ all ​0.4​s​; 
 ​} 
 ​form​ .​btn​:​hover​ .​inner​{ 
 ​  ​left​:​ ​0​; 
 ​} 
 ​form​ .​btn​ ​button​{ 
 ​  ​height​:​ ​100​%​; 
 ​  ​width​:​ ​100​%​; 
 ​  ​background​:​ none; 
 ​  ​border​:​ none; 
 ​  ​color​:​ ​#​fff​; 
 ​  ​font-size​:​ ​18​px​; 
 ​  ​font-weight​:​ ​500​; 
 ​  ​text-transform​:​ uppercase; 
 ​  ​letter-spacing​:​ ​1​px​; 
 ​  ​cursor​:​ pointer; 
 ​} 
 ​form​ .​signup-link​{ 
 ​  ​text-align​:​ center; 
 ​} 
 ​form​ .​signup-link​ ​a​{ 
 ​  ​color​:​ ​#​3498db​; 
 ​  ​text-decoration​:​ none; 
 ​} 
 ​form​ .​signup-link​ ​a​:​hover​{ 
 ​  ​text-decoration​:​ underline; 
 ​} 
 ​      ​</​style​> 
 ​   ​</​head​> 
 ​   ​<​body​> 
  
  
 ​    ​<​img​ ​src​="​sp3_2.jpg​" ​alt​="​Flowers in Chania​"​> 
  
 ​      ​<​div​ ​class​="​center​"​> 
 ​         ​<​input​ ​type​="​checkbox​" ​id​="​show​"​> 
 ​         ​<​label​ ​for​="​show​" ​class​="​show-btn​"​>​Click here​</​label​> 
 ​         ​<​div​ ​class​="​container​"​> 
 ​             
 ​            ​<​div​ ​class​="​text​"​> 
 ​               Login Form 
 ​            ​</​div​> 
 ​            ​<​form​ ​action​="​#​"​> 
 ​               ​<​div​ ​class​="​data​"​> 
 ​                  ​<​label​>​Email or Phone​</​label​> 
 ​                  ​<​input​ ​type​="​text​" ​required​> 
 ​               ​</​div​> 
 ​               ​<​div​ ​class​="​data​"​> 
 ​                  ​<​label​>​Password​</​label​> 
 ​                  ​<​input​ ​type​="​password​" ​required​> 
 ​               ​</​div​> 
 ​               ​<​div​ ​class​="​forgot-pass​"​> 
 ​                  ​<​a​ ​href​="​#​"​>​Forgot Password?​</​a​> 
 ​               ​</​div​> 
 ​               ​<​div​ ​class​="​btn​"​> 
 ​                  ​<​div​ ​class​="​inner​"​>​</​div​> 
 ​                  ​<​button​ ​type​="​submit​"​>​login​</​button​> 
 ​               ​</​div​> 
 ​               ​<​div​ ​class​="​signup-link​"​> 
 ​                  Not a member? ​<​a​ ​href​="​#​"​>​Signup now​</​a​> 
 ​               ​</​div​> 
 ​            ​</​form​> 
 ​         ​</​div​> 
 ​      ​</​div​> 
 ​   ​</​body​> 
 ​</​html​>
