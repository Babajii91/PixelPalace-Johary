<style lang="css" src="./global.css"></style>

<div class="container-SignIn">
    <h2>Sign In</h2>
    <input type="email" placeholder="Email" bind:value={email} />
    <input type="password" placeholder="Password" bind:value={password} />
    <button on:click={signin}>Sign In</button>
</div>