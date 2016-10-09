# Hidden-Eye
Android Hidden Camera demo, an example of how android apps can take pictures without your knowledge
# Tips: 
- Android SurfaceView (android.view.SurfaceView) is the object that can hold the camera view .
- A FrameLayout object can hold other content on the layout ressource files , It can be used as a placeHolder and can also have no size
# Example :
<FrameLayout
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:layout_weight="0"
        android:id="@+id/surfaceLayout">
        <!--Insert any object here and it will not be visible-->
</FrameLayout>

#What's Next for this app:
we aim to change this app to take photos in lapse of time and to save them on externalm storage.
