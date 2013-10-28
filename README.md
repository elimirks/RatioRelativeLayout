RatioRelativeLayout
===================

An Android widget for creating a relative container dependent on the layout width.

XML layout example:

	<my.package.RatioRelativeLayout
		android:layout_width="fill_parent"
		android:layout_height="wrap_content"
		heightRatio="0.75"
	>
		<TextView
			android:layout_width="25dp"
			android:layout_height="match_parent"
		/>
	</my.package.RatioRelativeLayout>

