<template>
  <div id="wrapper">
  	<nav class="navbar navbar-default">
  		<div class="container">
  			<a class="navbar-brand" href="#">
  				
  					<img src="././assets/logo.png" style="width:38px;height:38px;">
  			</a>
  			<ul class="nav navbar-nav">
  				<li class="activeColor"><router-link to="/home">��ҳ</router-link></li>

  				<li><router-link to="/new-list">�ղؼ�</router-link></li>

          <li><router-link to="/label">��ǩ</router-link></li>
          <li><input type="text" placeholder="�������" style="border:1px solid #f0eded;height:30px;padding:0px 10px;margin-top:10px;"></li>
          <li><router-link to="/user">Ͷ��</router-link></li>
          <li><router-link to="/user">��¼</router-link></li>
  			</ul>
  		</div>
  	</nav>
  	<div class="container">
  		<div class="col-sm-12">
  			<router-view></router-view>
  		</div>
  	</div>
  	
  </div>
</template>
<script>
import Sidebar from './components/Sidebar.vue'

export default{
	components:{'sidebar':Sidebar}
}

</script>
<style>
.activeColor{color:blue}
</style>



