<script lang="ts">
	import { Presentation, Slide, Stack, Step, Code } from '@components'

	let count = 0

	function handleClick() {
		count += 1
	}
</script>

<Presentation>
	<Slide>
		<section class="py-10 sm:py-16 lg:py-24">
			<div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
				<div
					class="grid items-center grid-cols-1 gap-12 lg:grid-cols-2 lg:text-left"
				>
					<div>
						<h1 class="tracking-tight font-extrabold text-gray-900">
							<span class="block xl:inline text-white text-5xl"
								>That Time I Underwent OJT @</span
							>
							<span class="block text-teal-500 xl:inline text-5xl"
								>PIXEL8 Web Solutions & Consultancy</span
							>
						</h1>
					</div>

					<div>
						<img class="w-full" src="hero.png" alt="" />
					</div>
				</div>
			</div>
		</section>
	</Slide>

	<Slide animate>
		<div
			class="flex flex-col lg:h-[400px] h-[800px] items-center justify-center"
		>
			<img
				class="lg:w-[400px] lg:h-[400px] w-[800px] h-[800px] object-cover"
				src="qr_code.svg"
				alt=""
			/>
			<p class="text-4xl text-teal-300 font-semibold mt-4">
				ojt-ppt-final.vercel.app
			</p>
		</div>
	</Slide>

	<Slide>
		<p class="text-5xl text-teal-300 font-semibold">
			Kung kaya mong gawin bukas, bakit mo pa gagawin ngayon?
		</p>
		<p class="mt-12 text-xl">– anonymous</p>
	</Slide>

	<Slide>
		<p class="text-5xl text-teal-300 font-semibold">
			Any fool can write code that a computer can understand. Good programmers
			write code that humans can understand.
		</p>
		<p class="mt-12 text-xl">– Martin Fowler</p>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				Brief Overview
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-between">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				Brief Overview
			</p>
			<img src="ico.png" class="h-[10rem]" alt="" />
			<p class="text-4xl text-teal-300 tracking-tight font-extrabold">
				PIXEL8 Web Solutions & Consultancy
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-between">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				Brief Overview
			</p>
			<img src="location.jpeg" class="mt-12 h-[24rem]" alt="" />
			<p class="text-lg text-teal-300 tracking-tight font-extrabold mt-8">
				Main Office: <span class="text-white"
					>Corner Albay 647, Legazpi City, Albay</span
				>
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-between">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				Brief Overview
			</p>
			<p class="text-4xl text-teal-300 tracking-tight font-extrabold mt-12">
				Services Offered
			</p>
			<div
				class="text-2xl text-white tracking-tight text-left lowercase mt-8 space-y-2"
			>
				<p>‣ WEBSITE DEVELOPMENT</p>
				<p>‣ SEARCH ENGINE OPTIMIZATION</p>
				<p>‣ SOCIAL MEDIA MARKETING</p>
				<p>‣ CONTENT MANAGEMENT</p>
				<p>‣ MOBILE APPLICATION</p>
				<p>‣ INFORMATION SYSTEM</p>
				<p>‣ BRANDING DESIGN</p>
				<p>‣ IT CONSULTANCY</p>
			</div>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				The Opportunity
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-between">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				The Opportunity
			</p>

			<img src="fb_post.jpg" class="mt-12 h-[24rem]" alt="" />
			<p class="text-4xl text-teal-300 tracking-tight font-extrabold mt-8">
				FB Post
			</p>
		</div>
	</Slide>

	<Slide>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				Our Background
			</p>
		</div>
	</Slide>

	<Slide>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<img src="languages.png" class="mt-12 h-[28rem]" alt="" />
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				The Journey
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				The Journey
			</p>
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold mt-8">
				First Impressions
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				The Journey
			</p>
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				Getting Started
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<img src="tech_stack.png" class="mt-12 h-[28rem]" alt="" />
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				The Journey
			</p>
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				Learning Curve
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="mx-auto w-[800px] text-4xl">
			<Code lang="html" lines="3-7|2,8|1-9">
				{`
            <template>
                <q-card class="counter-card">
                    <q-card-section>
                        <span class="counter-value" @click="increment">
                            clicks: {{ count }}
                        </span>
                    </q-card-section>
                </q-card>
            </template>
        `}
			</Code>
		</div>
		<div
			data-id="circle"
			class="mx-auto mt-8 w-[400px] rounded-2xl bg-gray-800"
		>
			<button on:click={handleClick}>
				clicks: {count}
			</button>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				The Journey
			</p>
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				Collaboration
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-between">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				Collaboration
			</p>

			<Stack>
				<img src="skype.png" class="mt-12 h-[24rem]" alt="" />

				<Step>
					<img src="team_call.png" class="mt-12 h-[24rem]" alt="" />
				</Step>

				<Step>
					<img src="team_call2.png" class="mt-12 h-[24rem]" alt="" />
				</Step>

				<Step>
					<img src="live_share.png" class="mt-12 h-[24rem]" alt="" />
				</Step>
			</Stack>

			<p class="text-4xl text-teal-300 tracking-tight font-extrabold mt-4">
				Skype and VsCode
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				The Journey
			</p>
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				Challenges and Growth
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				Reflection
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">Reflection</p>
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				Achievements
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				Achievements
			</p>
			<div
				class="grid grid-cols-1 gap-8 mt-10 text-center lg:mt-24 sm:gap-x-8 md:grid-cols-3"
			>
				<div>
					<h3 class="font-bold text-7xl">
						<span class="text-teal-300"> 29 </span>
					</h3>
					<p class="mt-4 text-lg font-medium text-white">UI/UX Design</p>
				</div>
				<div>
					<h3 class="font-bold text-7xl">
						<span class="text-teal-300"> 27 </span>
					</h3>
					<p class="mt-4 text-lg font-medium text-white">Frontend</p>
				</div>
				<div>
					<h3 class="font-bold text-7xl">
						<span class="text-teal-300"> 29 </span>
					</h3>
					<p class="mt-4 text-lg font-medium text-white">Backend</p>
				</div>
			</div>
			<p class="text-4xl text-teal-300 tracking-tight font-extrabold mt-24">
				Tasks Completed
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">
				Achievements
			</p>
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold mt-24">
				4 of us Became Team Leader
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">Reflection</p>
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">
				Lessons Learned
			</p>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">Reflection</p>
			<p class="text-4xl text-teal-300 tracking-tight font-extrabold mt-8">
				Lessons Learned
			</p>
			<div class="text-2xl text-white tracking-tight text-left mt-8 space-y-2">
				<p>‣ Real-World Application</p>
				<p>‣ Adaptation to Technology</p>
				<p>‣ Effective Communication</p>
				<p>‣ Teamwork Dynamics</p>
				<p>‣ Time Management</p>
				<p>‣ Professionalism</p>
				<p>‣ Resilience</p>
			</div>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex flex-col h-[400px] items-center justify-center">
			<p class="text-lg text-gray-300 tracking-tight font-normal">Reflection</p>
			<p class="text-6xl text-teal-300 tracking-tight font-extrabold">Advice</p>
		</div>
	</Slide>

	<Slide animate>
		<img class="w-full h-full object-cover" src="advice.png" alt="" />
	</Slide>
</Presentation>
