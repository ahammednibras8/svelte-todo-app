<script>
	function addTask() {
		console.log("Add Task Button Clicked");
	}

	let taskCount = 4;
</script>

<div>
	<div class="flex items-center space-x-3">
		<input
			class=" border border-[#3E1671] bg-transparent text-white placeholder-[#777777] px-4 py-2 rounded-lg focus:outline-none focus:ring-2 focus:ring-[#3E1671] focus:ring-opacity-50 h-12"
			type="text"
			placeholder="Add a new task"
		>
		<button
			class="bg-[#9E78CF] text-white p-3 rounded-lg hover:bg-[#7e62b1] transition duration-300 ease-in-out focus:outline-none focus:ring-2 focus:ring-[#3E1671] focus:ring-opacity-50 h-12 w-12 flex items-center justify-center"
			on:click={addTask}
			aria-label="Add a new task"
		>
			<img src="src/assets/hero-icons/plus.svg" alt="Add task icon" class="h-6 w-6" />
		</button>
	</div>
	<div>
		<p class="text-white py-6">Task to do - {taskCount}</p>
	</div>
	<div class="h-[75px] w-[432px] bg-[#15101C] rounded-lg">
		<div class="px-[20px] py-[22px] flex items-center justify-between">
			<p>Task Name</p>
			<div class="flex items-center justify-between space-x-3">
				<img src="src/assets/hero-icons/tick.svg" alt="Done" class="h-6 w-6" />
				<img src="src/assets/hero-icons/trash.svg" alt="Delete" class="h-6 w-6" />
			</div>
		</div>
	</div>
</div>


