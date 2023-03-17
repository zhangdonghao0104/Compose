# Compose
Compose学习记录
##环境搭建
app build.gradle->
buildFeatures {
//开启Compose与data
compose true
}
android {
composeOptions {
kotlinCompilerExtensionVersion '1.3.2'
}
}
添加依赖
implementation "androidx.compose.ui:ui-tooling-preview:1.2.1"       //在Android studio里预览ui的基础库


    
