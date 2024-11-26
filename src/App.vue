
    < 分 > ​​
      < 分 等级 = "bgBox"    V动作 :initial= "   {    不透明 : 0 , y : 25    }   " :enter= "   {    不透明 : 1 , y : 0    }   " :duration= "   1000   "   >
        < 信息组 SRC = “https://bitiful.814925.xyz/2024/11/26/202411261352443.png”    阿尔特 = “”  >
       </ 分 > ​​

       < div类= "bgGrid" >
         < 分 等级 = "Grid"     V动作 :initial= "    {     不透明 : 0 , y : - 25     }    " :enter= "    {     不透明 : 1 , y : 0     }    " :duration= "    1000    "    >
           < 分 等级 = " mask "    >    </ 分>
           < 分 等级 = "itemGrid-row"     电视机 = " 我 在…中 格里德罗斯 " :key= " 我 "    >
             < 分 等级 = "itemGrid-cols"     电视机 = " j 在…中 乙二醇 " :key= " j "    >    </ 分 >
           </ 分 > ​​
         </ 分 > ​​
      </ 分 > ​​

       < 分 等级 = "main"     V动作 :initial= "    {     不透明 : 0     }    " :enter= "    {     不透明 : 1     }    " :duration= "    1000    "    >
         < div类= “信息” >
           < div类= “标题” >
             < 信息组 SRC = “https://bitiful.814925.xyz/2024/11/16/202411161427657.png”     阿尔特 = “”    >
         </ 分 > ​​

           < div类= “信息文本” >
            < h1 > 嗨， </ h1 > ​​​
           < h1 > 我是 < 间隔 等级 = " qn "  > 佩奇 </ 间隔 >  </ h1 > ​​​
         </ 分 > ​​
       </ 分 > ​​

       < 分 等级 = “打字机”  >
         < 我 等级 = "宝家水族图2"  >  </ 我 >
          < 打字:字符串= " 打字文本 " :startDelay= "  300  " :typeSpeed= "  100  " :backSpeed= "  30  " :loop= "  真实的  "
          :showCursor= “真”  >
          </ 打字机 > ​​
           < 我 等级 = "圣像-保家水转向"    >   </ 我 >
       </ 分 > ​​

       < div类= “btns” >
        <a v-for = " 我 在…中 名单 " :key= " 我。 活泼的  " :href= " 我。 高参考值  "  目标 = "_blank"  > ​​​​​​​​​​​​​​​​​​ ​​​​
           < VS按钮 类型 = "gradient" : 颜色 = " i.color "  动画类型 = "scale"  > 
             < I:班级= "  `iconfont $ { i.icon } `  "  >  </ 我 >

              < 模板 #有动画   >
              {{ 我。动画 }}
              </ 模板 >
            </ vs-按钮 >
          </ 一 >

          < VS按钮 等级 = “lastBtn”    颜色 = “#457B9D”    动画类型 = “scale” @click = “   活跃的 = 真实的   ”   >
            < 我 等级 = "圣像"   >   </ 我 >

            < 模板 #有动画   >
            关于
            </ 模板 >
          </ vs-按钮 >
      </div>
    </div>

     < div类= “页脚” >
       < b > < A 高参考值 = "https://814925.xyz/"  目标 = "_blank" > By佩奇©2024 </ A > </ b > | ©2024  | < b > < A 高参考值 = "https://beian.miit.gov.cn/"  目标 = "_blank" > 渝ICP备-2024044325号 </ A > </ b >
    </div>​​

    < vs-dialog覆盖模糊 宽度= "550px" 非中心 v-model = "活动" >
      <模板#header >
        < h2 class = "无保证金" >
          关于本站
        </h2>​​
      </模板>

      < div class = “con-content” >

        < vs-alert color = "#FE8599"  type = "gradient"  v-model :hidden -content = " techHidden " >
          <模板#title >技术栈</模板>
          < p >本站以下基于技术架构和以下服务商部署</ p >

          < vs-avatar-group class = "aboutAva"  float  max = "8" >

            < vs-tooltipplacement = " top"  v-for = " i in avaters " : key= " i.content " >
              < vs -avatar :color= " i.color " >
                < i :class= " `iconfont $ { i.icon } ` " > </ i >
              </ vs-头像>

              <模板#content > {{ i.内容 }} </模板>
            </ vs-工具提示>

            <vs-tooltip placement="top">
              <vs-avatar color="#FF6D1A">
                初
              </vs-avatar>

              <template #content>初七云cdn</template>
            </vs-tooltip>

          </vs-avatar-group>
        </vs-alert>

        <vs-alert color="#00BCD4" type="gradient" v-model:hidden-content="aboutHidden">
          <template #title>关于项目</template>

          <p>你可以从这里访问 <b>我的博客、GitHub、哔哩哔哩、网易云歌单</b> 以及给我发 <b>邮件</b> ！</p>
          <p>本项目借鉴了
            <b><a href="https://pzj.us.kg/" target="_blank">pzjawa</a></b> 、
            <b><a href="https://www.liushen.fun/" target="_blank">清羽飞扬</a></b>
            等主页，感谢他们awa
          </p>
          <p>项目已经开源：</p>
          <p><a href="https://github.com/QNquenan/homepage-for-vue3"
              target="_blank">https://github.com/QNquenan/homepage-for-vue3</a>
          </p>
        </vs-alert>
      </div>

      <template #footer>
        <div class="con-footer">
          <div class="reTheme">

            <input type="radio" id="light" name="theme" :checked="theme == 'light'">
            <label @click="setTheme('light')" for="light">
              <i class="iconfont icon-baitian"></i>
            </label>

            <input type="radio" id="system" name="theme" :checked="theme == 'system'">
            <label @click="setTheme('system')" for="system">
              <i class="iconfont icon-gensuixitong"></i>
            </label>

            <input type="radio" id="dark" name="theme" :checked="theme == 'dark'">
            <label @click="setTheme('dark')" for="dark">
              <i class="iconfont icon-yewan"></i>
            </label>

            <div class="checkedBg"></div>
          </div>

          <div class="footerBtn">
            <vs-button color="#fe8599" @click="versions" type="border">
              当前版本
            </vs-button>
            <vs-button color="#fe8599" @click="active = false">
              知道啦
            </vs-button>
          </div>
        </div>
      </template>
    </vs-dialog>
  </div>
</template>

<script>
import { VsNotification } from 'vuesax-alpha'

export default {
  data() {
    return {
      techHidden: true,
      aboutHidden: true,
      typingTexts: [
        "你好鸭，欢迎来到我的主页！",
        "彼方尚有荣光在，世界不止眼前的苟且，还有诗和远方",
        "累了可以在我这里歇歇脚嗷",
        "May you happy every day",
      ],
      btnList: [
        {
          icon: 'icon-bokeshangse',
          animate: '博客',
          color: '#fe8599',
          href: 'https://hexo.814925.xyz'
        },
        {
          icon: 'icon-a-paishexiangji',
          animate: '时光相册',
          color: '#3d3d3d',
          href: 'https://github.com/RunWang925'
        },
        {
          icon: 'icon-icon-test',
          animate: '薯条是条条',
          color: '#0BA6D8',
          href: 'https://space.bilibili.com/495882959'
        },
        {
          icon: 'icon-youjian1',
          animate: 'E-mail',
          color: '#FACB1E',
          href: 'mailto:1104605271@qq.com'
        },
        {
          icon: 'icon-wangyiyunyinle1',
          animate: '网易云',
          color: '#D81E06',
          href: 'https://music.163.com/#/playlist?id=2696501847&creatorId=1785635020'
        },
      ],
      avaters: [
        {
          color: '#43B884',
          icon: 'icon-vue',
          content: 'Vue3'
        },
        {
          color: '#46C93A',
          icon: 'icon-vuesax-linear-vuesax',
          content: 'Vuesax for Vue3'
        },
        {
          color: '#1FD0ED',
          icon: 'icon-less',
          content: 'Less'
        },
        {
          color: '#FFBA00',
          icon: 'icon-vite',
          content: 'Vite'
        },
        {
          color: '#000',
          icon: 'icon-vercel',
          content: 'Vercel'
        },
        {
          color: '#000',
          icon: 'icon-github',
          content: 'Github'
        }
      ],
      upTime: '2024-09-16',
      version: 'beta3',
      gridRows: 9,
      gridCols: 5,
      active: false,
      isDarkMode: true,
      theme: 'system' // 默认是亮色模式
    }
  },
  mounted() {
    if (localStorage.getItem('isTheme')) {
      this.theme = localStorage.getItem('isTheme')
      this.applyTheme()
    } else {
      this.applyTheme()
    }
    // 监听系统主题变化
    window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', this.applyTheme);
  },
  methods: {
    setTheme(mode) {
      this.theme = mode;
      localStorage.setItem('isTheme', mode)
      this.applyTheme();
    },
    applyTheme() {
      const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
      const themeToApply = this.theme === 'system' ? (prefersDark ? 'dark' : 'light') : this.theme;
      document.documentElement.setAttribute('data-theme', themeToApply);
    },
    versions() {
      VsNotification({
        icon: '<i class="iconfont icon-guanyu"></i>',
        progressAuto: true,
        position: 'top-center',
        title: '当前的版本',
        color: '#FE8599',
        content: `现在是 ${this.upTime} 更新的 ${this.version}`
      })
    }
  }
}
</script>

<style lang="less">
@import url(//at.alicdn.com/t/c/font_4731772_7nzq4yla5mq.css);
/* 阿里巴巴图标库 */
</style>
