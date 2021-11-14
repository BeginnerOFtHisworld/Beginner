import os
import shutil
sourcepath=r'C:\\Users\\azeez\Desktop'
sourcefiles = os.listdir(sourcepath)
print(sourcefiles)
for e in sourcefiles:
    if e.endswith(".html"):
        os.chdir('C:\\Users\\azeez\\Desktop')
        print("working1")
        os.makedirs('C:\\Users\\azeez\\Desktop\\Please-Work2')
        print("working2")
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-html')
        print("done")
        break
for e in sourcefiles:
    if e.endswith(".html"):
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-html',e))
for e in sourcefiles:
    if e.endswith(".pdf"):
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-pdf')
        print("done <3")
        break
for e in sourcefiles:
    if e.endswith(".pdf"):
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-pdf',e))
        print('done for pdf')
for e in sourcefiles:        
    if e.endswith(".jpeg"):
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-jpeg')
        print("jepg is created <3")
for e in sourcefiles:
    if e.endswith(".jpeg"):
        print("is this working")
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-jpeg',e))
        print('done for jpeg')
for e in sourcefiles:        
    if e.endswith(".accdb"):
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-accdb')
        print("accdb is created <3")
for e in sourcefiles:
    if e.endswith(".accdb"):
        print("is this working")
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-accdb',e))
        print('done for accdb')
for e in sourcefiles:        
    if e.endswith(".jfif"):
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-jfif')
        print("jfif is created <3")
        break
for e in sourcefiles:
    if e.endswith(".jfif"):
        print("is this working")
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-jfif',e))
        print('done for jfif')
for e in sourcefiles:        
    if e.endswith(".py"):
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-py')
        print("jfif is created <3")
        break
for e in sourcefiles:
    if e.endswith(".py"):
        print("is this working")
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-py',e))
        print('done for py')
for e in sourcefiles:        
    if e.endswith(".c"):
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-c')
        print("c is created <3")
        break
for e in sourcefiles:
    if e.endswith(".c"):
        print("is this working")
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-c',e))
        print('done for c')
for e in sourcefiles:        
    if e.endswith(".pptx"):
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-pptx')
        print("pptx is created <3")
        break
for e in sourcefiles:
    if e.endswith(".pptx"):
        print("is this working")
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-pptx',e))
        print('done for pptx')
for e in sourcefiles:        
    if e.endswith(".psd"):
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-psd')
        print("psd is created <3")
        break
for e in sourcefiles:
    if e.endswith(".psd"):
        print("is this working")
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-psd',e))
        print('done for psd')
for e in sourcefiles:        
    if e.endswith(".mp4"):
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-mp4')
        print("mp4 is created <3")
        break
for e in sourcefiles:
    if e.endswith(".mp4"):
        print("is this working")
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-mp4',e))
        print('done for mp4')
for e in sourcefiles:        
    if e.endswith(".odt"):
        os.chdir('C:\\Users\\azeez\\Desktop\\Please-Work2')
        os.makedirs('os-this-is-for-odt')
        print("odt is created <3")
        break
for e in sourcefiles:
    if e.endswith(".odt"):
        print("is this working")
        shutil.move(os.path.join(sourcepath,e), os.path.join('C:\\Users\\azeez\\Desktop\\Please-Work2\\os-this-is-for-odt',e))
        print('done for odt')
