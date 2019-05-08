<template>
	<v-toolbar dark color="primary">
		<v-toolbar-side-icon large></v-toolbar-side-icon>
		<v-toolbar-title>Title</v-toolbar-title>
		<v-spacer></v-spacer>
		<v-toolbar-items>
			<v-btn icon>
				<v-icon large>search</v-icon>
			</v-btn>
			<v-btn icon>
				<v-badge overlap color="deep-orange">
					<template v-slot:badge>
						<span>2</span>
					</template>
					<v-icon large>shopping_cart</v-icon>
				</v-badge>
			</v-btn>
		</v-toolbar-items>
	</v-toolbar>
</template>