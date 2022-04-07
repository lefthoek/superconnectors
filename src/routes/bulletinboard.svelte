<script lang="ts">
	import BulletinBoard from '$components/Bulletinboard.svelte';
	import gStore from '$stores/gameData';
	import Timer from '$components/Timer.svelte';
</script>

<BulletinBoard fullscreen={true} askData={$gStore}>
	<Timer slot="footer" />
</BulletinBoard>
