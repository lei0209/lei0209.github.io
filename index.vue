<template>  
  <div class="background-image">  
    <a href=""><img src="../picture/logo.png" alt="叠加在背景上的logo" class="logo-image"></a>
   
    <p style="color: white; position: relative; left: 10%; top: 5%; " >
              <router-link to="/guwm"><span class="jianju">关于我们</span></router-link>
              <router-link to="/yxfw"><span class="jianju">运行服务</span></router-link>
              <router-link to="/fwtx"><span class="jianju">服务体系</span></router-link>
              <router-link to="/yyal"><span class="jianju">应用案例</span></router-link>
            </p>
            <router-link to="/zxkf">
              <img src="/src/picture/客服.png" alt="" class="follow1">
              <span class="follow2">联系我们</span></router-link>
             
            
            
    <img src="/src/picture/R-C.gif" alt="" class="follow">
    <h1 class="tycolor">人工智能简介</h1>  
    <p class="jieshao">人工智能（Artificial Intelligence），英文缩写为AI。 是新一轮科技革命和产业变革的重要驱动力量，是研究、开发用于模拟、延伸和扩展人的智能的理论、方法、技术及应用系统的一门新的技术科学。</p>
    <dl style="position: relative; top: 40%; left: 5%; font-family: 楷体;">
    <dt style="color: white; font-size: 20px;">2010年代早期</dt>
    <dd class="huise">随着大数据和云计算技术的兴起，人工智能开始进入新的发展阶段。</dd> <dd class="huise">机器学习算法，特别是深度学习，开始展现出强大的能力，<br>在图像识别、语音识别和自然语言处理等领域取得了显著突破。</dd>
    </dl>
    <dl style="position: relative; top: 27%; left: 45%; font-family: 楷体;">
      <dt style="color: white; font-size: 20px;">2012年</dt>
      <dd class="huise">深度学习在图像识别领域取得了重大突破，尤其是卷积神经网络（CNN）<br>在ImageNet挑战赛上的成功，引发了深度学习在AI领域的广泛关注和应用。</dd>
    </dl>
    <dl style="position: relative; top: 30%; left: 5%; font-family: 楷体;">
      <dt style="color: white; font-size: 20px;">2014年</dt>
      <dd class="huise">深度学习开始应用于自然语言处理（NLP）领域，取得了显著的进步。<br>同年，谷歌推出了基于深度学习的语音识别系统，大大提高了语音识别的准确率。</dd>
    </dl>
    <dl style="position: relative; top: 19%; left: 45%; font-family: 楷体;">
      <dt style="color: white; font-size: 20px;">2016年</dt>
      <dd class="huise">谷歌的DeepMind团队开发的AlphaGo系统在围棋比赛中击败了世界冠军李世石，<br>这一事件引起了全球对人工智能的广泛关注。<br>AlphaGo的成功展示了深度学习在解决复杂问题方面的潜力。</dd>
    </dl>
    <dl style="position: relative; top: 19%; left: 5%; font-family: 楷体;">
      <dt style="color: white; font-size: 20px;">2017年</dt>
      <dd class="huise">随着算法和计算力的进一步提升，人工智能开始在更多领域得到应用，<br>包括自动驾驶、医疗诊断、金融风控等。同时，各大科技公司和研究机构纷纷<br>加大在人工智能领域的投入，推动AI技术的快速发展。</dd>
    </dl>
    <dl style="position: relative; top: 6%; left: 45%; font-family: 楷体;">
      <dt style="color: white; font-size: 20px;">2018年至今</dt>
      <dd class="huise">人工智能的应用范围继续扩大，渗透到日常生活的各个方面。例如，智能音箱、<br>智能家居等产品的普及，使得人们可以更方便地与AI进行交互。<br>同时，人工智能也开始在解决社会问题方面发挥作用，如环境保护、能源管理等领域。</dd>
    </dl>
    <hr class="hr">
    <p class="phone">电话:010-58812000&nbsp;&nbsp;&nbsp;&nbsp;邮箱:58812000@cstnet.cn <br>
      ©1996 - 2021 人工智能网 版权所有 京ICP备09112257号-38</p>


       
  </div>  
</template>  
  
<style scoped>  
.follow{
  position: fixed;
  width: 100px;
  height: 100px;
  right: 0px;
  top: 85%;
}
.follow1{
  position: fixed;
  width: 100px;
  height: 100px;
  right: 6px;
  top: 38%;
}
.follow2{
  position: fixed;
  width: 100px;
  height: 100px;
  top: 52%;
  left: 94%;
  color: rgb(255, 223, 148);
}

.jianju{
  margin-right: 300px;
}
.huise{
  color: darkgrey;
  font-size: 16px;
}
.phone{
  color: chocolate;
  position: relative;
  top: 8%;
  left: 2%;
}
.hr{
  position: relative;
  top: 50px;
}
.background-image {  
  background-image: url('../picture/科技1.webp');  
  height: 100vh;  
  width: 100vw;  
  background-size: cover;  
  background-position: center;  
}  
  
.logo-image {  
  width: 200px;  
  height: auto;  
  position: absolute;  
  top: 10%; /* 根据需要调整 */  
  left: 50%;  
  transform: translate(-50%, -50%);  
}  
  
.text-container {  
  position: absolute; /* 绝对定位，以便可以相对于背景图片容器定位 */  
  bottom: 90%; /* 根据需要调整，使文字靠近底部 */  
  right: 0%;  
  text-align: center; /* 水平居中文字 */  
  color: rgb(150, 150, 150); /* 设置文本颜色 */  
}  
  
.text-item {  
  display: inline-block; /* 使p标签变成内联块级元素，可以并排显示 */  
  margin: 0 155px; /* 设置每个p标签之间的间距 */  
  font-size: 16px;  
}
.tycolor{
  position: absolute;
  color: white;
  text-align: center;
  bottom: 70%;
  right: 44%; 
}
.jieshao{
  position: absolute;
  color: white;
  text-align: center;
  bottom: 60%;
  right: 30%; 
  left: 30%;
  top: 27%;
}
.zhuisu{
  font-family: 楷体;
  position: absolute; /* 绝对定位，以便可以相对于背景图片容器定位 */  
  bottom: 35%; /* 根据需要调整，使文字靠近底部 */  
  left: 5%; 
  color: rgb(255, 255, 255); /* 设置文本颜色 */    
  font-size: 20px;  
}
</style>  
  
<script>  
export default {  
  data() {  
    return {  
    }
  }  
}  
</script>