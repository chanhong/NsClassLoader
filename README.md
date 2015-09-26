# NsClassLoader

Usage:

    NsClassLoader::$classFolders = array($path.DS."folder1",$path.DS."folder2",);
    
    $autoloader = new NsClassLoader();
    
This autoloader is developed for the ease of migrating over to use PHP namespace in class using aliases with existing code that was written before using namespace with minimum effort.    

Note: You must declar $classFolders so the NsClassLoaders will use them to do the auto loading.
