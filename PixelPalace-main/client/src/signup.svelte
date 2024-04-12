<style lang="css" src="./global.css"></style>

<div class="container-SignUp">
    <h2>Sign Up</h2>
    <input type="email" placeholder="Email" bind:value={email} />
    <input type="password" placeholder="Password" bind:value={password} />
    <input type="password" placeholder="Confirm Password" bind:value={confirmPassword} />
    <button on:click={signup}>Sign Up</button>
</div>