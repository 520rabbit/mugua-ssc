<template>
    <div>
      <div class="Job-footer clearfix">
      <div class="Jobf-content">
        <div class="Jobco-left"><a href="http://www.jobyes.com/index" target="_blank"  style="width: 89px; display:block;"><img src="@/assets/images/jzlogo.png" style="width: 100%;"></a></div>
        <div class="Jobco-help">
          <ul>
            <li><a href="http://www.jobyes.com/info/RecruitmentServiceAgreement" target="_blank">招聘服务协议</a></li>
            <li><a href="http://www.jobyes.com/info/JobPublishingRule" target="_blank">职位发布规则</a></li>
            <li><a href="http://www.jobyes.com/info/UserCompetitionRules" target="_blank">求职者竞聘规则</a></li>
            <li><a href="http://www.jobyes.com/info/Privacypolicy" target="_blank">隐私政策</a></li>
            <li><a href="http://www.jobyes.com/info/LegalStatement" target="_blank">法律声明</a></li>
          </ul>
        </div>
        <div class="Jobco-help">
          <ul>
            <li><a href="http://www.jobyes.com/info/Winwincooperation" target="_blank">合作共赢</a></li>
            <li><a href="http://www.jobyes.com/info/About" target="_blank">关于我们</a></li>
            <li><a href="http://www.jobyes.com/info/JoinUs" target="_blank">加入我们</a></li>
            <li><a href="http://www.jobyes.com/info/ProductService" target="_blank">产品服务</a></li>
            <li><a href="#">意见反馈</a></li>
          </ul>
        </div>
        <div class="Jobco-wei">
          <span>扫描关注公众号</span>
          <img src="@/assets/images/qrcode_jz.jpg" />
        </div>
        <div class="Jobco-tel">
          <div class="xian">招聘服务热线</div>
          <div class="phone">020-81747580</div>
          <div class="xian">工作日 </div>
          <div class="time">9:00-19:00</div>
        </div>
      </div>
    </div>
    <div class="Job-Copyright">Copyright © 20019-2029 www.jobyes.com All Rights Reserved  <a href="http://www.beian.gov.cn/portal/index">粤公网安备 44010502001414号</a>  </div>
    </div>
</template>

<script>
export default {
    nane: 'Footer'
}
</script>

<style  scoped>
.Job-footer{
	width: 100%;
	background-color: #222222;
	padding: 30px 0;
}
.Job-footer .Jobf-content{
	width: 1200px;
	margin: auto;
}
.Job-footer .Jobf-content{
	width: 1200px;
	margin: auto;
}
.Job-footer .Jobf-content .Jobco-left{
	width: 150px;
	float: left;
}
.Job-footer .Jobf-content .Jobco-help{
	width: 180px;
	float: left;
	font-size: 12px;
}
.Job-footer .Jobf-content .Jobco-help ul{
	margin: 0;
	padding: 0;
}
.Job-footer .Jobf-content .Jobco-help ul li{
	color: #666666;
	padding-bottom: 9px;
}
.Job-footer .Jobf-content .Jobco-help ul li a{
	color: #888888;
}
.Job-footer .Jobf-content .Jobco-help ul li a:hover{
	color: #FFFFFF;
}
.Job-footer .Jobf-content .Jobco-tel{
	width: 300px;
	float: right;
	font-size: 12px;
	position: relative;
	padding: 0 50px;
}
.Job-footer .Jobf-content .Jobco-tel:before{
	position: absolute;
    width: 1px;
    height: 70px;
    content: '';
    right: 0;
    top: 20px;
    background-color: #4b4b4b;
}
.Job-footer .Jobf-content .Jobco-tel:after{
	position: absolute;
    width: 1px;
    height: 70px;
    content: '';
    left: 0;
    top: 20px;
    background-color: #4b4b4b;
}
.Job-footer .Jobf-content .Jobco-tel .xian{
	font-size: 12px;
	color: #888888;
	padding-bottom: 8px;
}
.Job-footer .Jobf-content .Jobco-tel .phone{
	font-size: 25px;
	font-weight: bold;
	color: #888888;
	padding-bottom: 12px;
}
.Job-footer .Jobf-content .Jobco-tel .time{
	font-size: 20px;
	font-weight: bold;
	color: #888888;
}
.Job-footer .Jobf-content .Jobco-wei{
	width: 180px;
	float: right;
	padding-left: 50px;
}
.Job-footer .Jobf-content .Jobco-wei span{
	color: #888888;
	margin-bottom: 9px;
	display: block;
}
.Job-footer .Jobf-content .Jobco-wei img{
	width: 130px;
	height: 130px;
}
.Job-Copyright {
	width: 100%;
	height: 50px;
	line-height: 50px;
	background-color: #191919;
	text-align: center;
	font-size: 12px;
	color: #5f5f5f;
}

 
</style>