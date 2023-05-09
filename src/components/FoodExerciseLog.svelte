<script lang='ts'>
    export let underGoal: boolean;
    export let goalDelta: number;
    export let mainMealsCount: number;
    export let mealsList: string[];
    export let snacksList: string[];
    export let didPT: boolean;
    export let exerciseSummary: string;
    export let exerciseList: string[];
    export let otherThoughts: string='';
</script>

<div>
    <h3 class='font-bold'>Food</h3>
    <br />
    <p>{underGoal ? 'Under' : 'Over'} calorie goal by {goalDelta}.</p>
    <br />
    <p>{mainMealsCount} main meals:</p>
    <ul class='list-disc ml-10 my-3'>
        {#each mealsList as meal}
            <li>
                {meal}
            </li>
        {/each}
    </ul>
    <p>Snacks</p>
    <ul class='list-disc ml-10 my-3'>
        {#each snacksList as snack}
            <li>{snack}</li>
        {/each}
    </ul>

    <br />

    <h3 class='font-bold'>PT (Physical Therapy)</h3>
    <br />
    <p>{didPT ? 'Yes' : 'No'}</p>

    <br />

    <h3 class='font-bold'>Exercise</h3>
    <br />
    <p>{exerciseSummary ? `${exerciseSummary}:` : 'No exercise today.'}</p>
    <ul class='list-disc ml-10 my-3'>
        {#each exerciseList as exercise}
            <li>{exercise}</li>
        {/each}
    </ul>

    {#if otherThoughts}
        <br />

        <h3>Other Thoughts</h3>
        <br />
        <p>{otherThoughts}</p>
    {/if}
</div>