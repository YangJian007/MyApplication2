# MyApplication2

1.Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
	
2. Add the dependency
		
	dependencies {
	    compile 'com.github.YangJian007:MyApplication2:v1.0.0'
	}
	
3.
	startActivity(new Intent(this, LibraryActivity.class));