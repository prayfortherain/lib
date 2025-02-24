# lib



dependencies {

    implementation(libs.androidx.core.ktx)
    implementation(libs.androidx.lifecycle.runtime.ktx)
    implementation(libs.androidx.activity.compose)
    implementation(platform(libs.androidx.compose.bom))
    implementation(libs.androidx.ui)
    implementation(libs.androidx.ui.graphics)
    implementation(libs.androidx.ui.tooling.preview)
    implementation(libs.androidx.material3)
    testImplementation(libs.junit)
    androidTestImplementation(libs.androidx.junit)
    androidTestImplementation(libs.androidx.espresso.core)
    androidTestImplementation(platform(libs.androidx.compose.bom))
    androidTestImplementation(libs.androidx.ui.test.junit4)
    debugImplementation(libs.androidx.ui.tooling)
    debugImplementation(libs.androidx.ui.test.manifest)



    //di
    implementation("com.google.dagger:hilt-android:2.38.1")
    ksp("com.google.dagger:hilt-android-compiler:2.38.1")
    ksp("androidx.hilt:hilt-compiler:1.2.0")
    implementation("androidx.activity:activity-ktx:1.10.0")

    //navigation
    implementation("androidx.navigation:navigation-compose:2.8.7")

    //room
    implementation("androidx.room:room-runtime:2.6.1")
    ksp("androidx.room:room-compiler:2.6.1")
    implementation("androidx.room:room-ktx:2.6.1")

    //coil
    implementation("io.coil-kt:coil:2.2.2")

    //serialization
    implementation("org.jetbrains.kotlinx:kotlinx-serialization-json:1.8.0")

    //retrofit
    implementation("com.squareup.retrofit2:retrofit:2.0.0")
    implementation("com.squareup.retrofit2:converter-gson:2.0.0")

}



plugins {
    alias(libs.plugins.android.application)
    alias(libs.plugins.kotlin.android)
    alias(libs.plugins.kotlin.compose)

    id("com.google.devtools.ksp")
    id("org.jetbrains.kotlin.plugin.serialization")
}




project

id("com.google.devtools.ksp") version "2.1.0-1.0.29"
id("org.jetbrains.kotlin.plugin.serialization") version "2.1.10" apply false



147.45.185.106

//
