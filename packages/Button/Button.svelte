<script>
	export let variant = "primary";
</script>

<style>
	button {
	  color: white;
	  border: none;
	  padding: 1rem 3rem;
	  border-radius: 40px;
	  letter-spacing: 0.75px;
	  transition: 0.3s;
	  cursor: pointer;
	  font-family: "Poppins";
	}

	.primary {
	  background: #5f2eea;
	}
	.primary:hover {
	  background: #2a00a2;
	}
	.primary:focus {
	  outline: none;
	  box-shadow: 0 0 0 6px #e4daff;
	}

	.secondary {
	  background: none;
	  border: 2px solid #5f2eea;
	  color: #5f2eea;
	  font-weight: bold;
	}
	.secondary:hover {
	  border: 2px solid #2a00a2;
	  color: #2a00a2;
	}
	.secondary:focus {
	  outline: none;
	  box-shadow: 0 0 0 6px #eff0f6;
	}
</style>



<button class={variant}>
  <slot></slot>
</button>