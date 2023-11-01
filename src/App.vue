<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

<!-- ---------------------------BS測試開始-------------------------------------- -->

	<!-- 網格系統 -->
	<div class="container-xl">
		<div class="container text-center">
			<div class="row align-items-start">
				<div class="col-6 text-primary">
					One of three columns
				</div>
				<div class="col-3 text-danger">
					One of three columns
				</div>
				<div class="col-3 text-warning">
					One of three columns
				</div>
			</div>
		</div>
	</div>


	<!-- 導覽列 -->
	<nav class="navbar navbar-expand-lg bg-body-tertiary">
		<div class="container-fluid">
			<a class="navbar-brand" href="#">Navbar</a>
			<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
				aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>
			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav me-auto mb-2 mb-lg-0">
					<li class="nav-item">
						<a class="nav-link active" aria-current="page" href="#">Home</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="#">Link</a>
					</li>
					<li class="nav-item dropdown">
						<a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
							aria-expanded="false">
							Dropdown
						</a>
						<ul class="dropdown-menu">
							<li><a class="dropdown-item" href="#">Action</a></li>
							<li><a class="dropdown-item" href="#">Another action</a></li>
							<li>
								<hr class="dropdown-divider">
							</li>
							<li><a class="dropdown-item" href="#">Something else here</a></li>
						</ul>
					</li>
					<li class="nav-item">
						<a class="nav-link disabled" aria-disabled="true">Disabled</a>
					</li>
				</ul>
				<form class="d-flex" role="search">
					<input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
					<button class="btn btn-outline-success" type="submit">Search</button>
				</form>
			</div>
		</div>
	</nav>


	<!-- 手風琴 -->
	<div class="accordion" id="accordionExample">
		<div class="accordion-item">
			<h2 class="accordion-header">
				<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne"
					aria-expanded="true" aria-controls="collapseOne">
					Accordion Item #1
				</button>
			</h2>
			<div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
				<div class="accordion-body">
					<strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse
					plugin adds the appropriate classes that we use to style each element. These classes control the overall
					appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with
					custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go
					within the <code>.accordion-body</code>, though the transition does limit overflow.
				</div>
			</div>
		</div>
		<div class="accordion-item">
			<h2 class="accordion-header">
				<button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
					data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
					Accordion Item #2
				</button>
			</h2>
			<div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
				<div class="accordion-body">
					<strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse
					plugin adds the appropriate classes that we use to style each element. These classes control the overall
					appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with
					custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go
					within the <code>.accordion-body</code>, though the transition does limit overflow.
				</div>
			</div>
		</div>
		<div class="accordion-item">
			<h2 class="accordion-header">
				<button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
					data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
					Accordion Item #3
				</button>
			</h2>
			<div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
				<div class="accordion-body">
					<strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse
					plugin adds the appropriate classes that we use to style each element. These classes control the overall
					appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with
					custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go
					within the <code>.accordion-body</code>, though the transition does limit overflow.
				</div>
			</div>
		</div>
	</div>


<!-- ---------------------------BS測試結束-------------------------------------- -->

	<div>
		<a href="https://vitejs.dev" target="_blank">
			<img src="/vite.svg" class="logo" alt="Vite logo" />
		</a>
		<a href="https://vuejs.org/" target="_blank">
			<img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
		</a>
	</div>

	<HelloWorld msg="Vite + Vue" />
</template>

<style scoped>.logo {
	height: 6em;
	padding: 1.5em;
	will-change: filter;
	transition: filter 300ms;
}

.logo:hover {
	filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
	filter: drop-shadow(0 0 2em #42b883aa);
}</style>
