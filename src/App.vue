<template>
	<div class="App">
		<header class="App-header">
			<button @click="test">Test</button>
		</header>
	</div>
</template>

<script>
  export default {
    data() {
      return {
        message: "Learn Vue"
      };
    },
	methods: {
      test() {
        alert('super duper ')
	  }
	}
  };
</script>

<style>
	.App {
		text-align: center;
	}
	.App-header {
		background-color: #f9f6f6;
		color: #32485f;
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		font-size: calc(10px + 2vmin);
	}
	.App-link {
		color: #00c185;
	}
	.App-logo {
		height: 40vmin;
		pointer-events: none;
		margin-bottom: 1rem;
		animation: App-logo-spin infinite 1.6s ease-in-out alternate;
	}
	@keyframes App-logo-spin {
		from {
			transform: scale(1);
		}
		to {
			transform: scale(1.06);
		}
	}
</style>
