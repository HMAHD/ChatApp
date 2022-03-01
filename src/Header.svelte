<header>
<h1>Chat App ✒️</h1>
{#if $username}
<div class="user-bio">
    <span> Hello 👋 <strong>{$username}</strong></span>
    <img src={'https://avatars.dicebear.com/api/human/${$username}'}.svg'} 
</div>

<button class="signout-button" on:click={signout}>Sign out</button>
{:else}
<h3>Chat App ⛓</h3>
{/if}
</header>