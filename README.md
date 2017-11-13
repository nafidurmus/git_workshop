git hakkında yararlı bilgiler

#### **Kurulum**
- [Mac OS](https://git-scm.com/download/mac)
- [Windows](https://git-scm.com/download/win)
- [Linux](https://git-scm.com/download/linux)



#### **Git Cheat Sheet**

##### **Oluşturma**

- **git clone clonlanacak_url** : Clonlamak için 
- **git init**: yeni local repo oluşturma 

##### **Yerel repoda değişikler**

 - **git status** : çalıştığımız repoda bir değişiklik varsa değişikliği gösterir
 - **git diff <kaynak_dal><hedef_dal>**: değişikleri birleştimeden önce önizleme yapmak   
 - **git add .** : değişiklik olan    bütün   
 - **git add -p <dosya_adi>**:  belirtilen dosyayı yerel repoya gönderme    
 -  **git commit -m "yorum"**
 - **git commit -a** :     
 - **git commit --amend**:

##### **yapılan commitleri Listeleme**

- **git log**: bütün commitleri listelemek için
- **git log -p <dosya_adi>** : seçili dosyaya ait commitleri listelemek için
- **git blame <dosya_adi>**:

##### **dallanmalar ve etiketler**

- **git branch -av**:
- **git checkout <branch(dallanma)>** :
- **git branch <yeni_dallanma>**: yeni dallanma oluşturma
- **git checkout --track <remote/branch>** :
- **git branch -d <dallanma>**: local repodaki dallanmayı silme
- **git tag <etiket_ismi>** : etiketle sürüm numarası oluşturmak.(git tag 1.0.0)


##### **Güncelleme ve yayınlama**

- **git remote -v** : şu ana kadar yapılmış bütün uzak repoya eklemeleri listeler
- **git remote show <remote>**: uzak repoya gönderimler hakkında bilgi verir.
- **git remote add <kisa_adlandirma> <url>** : yeni bir uzak repo oluşturur. ><remote> isimli
- **git fetch <remote>** : uzak repodaki bütün değişkleri indirmeye yarar.fakat birleştirme yapmaz
- **git pull <remote> <branch>** : uzak repodaki değişkleri indirir ve birleştirir.
- **git branch -dr <remote/branch>** : uzak repodaki dallanmayı siler.
- **git push --tags** : etiketleri yayınlar.


##### **Birleştime** 

- **git merge <branch>**: dallanmayı senin reponla birleştirmeye yarar.
- **git rebase <branch>** : merge gibi fakat dallanma ile alakalı bir kayıt kalmaz.
- **git rebase --abort**: rebase i iptal etmek
- **git rebase --continue**: sorunları çözdükren sonra rebase ile devam etmek için.
- **git mergetool**: 
- **git add <resoved_file>** : ekleme
- **git rm <resoved_file>** : ortadan kaldırma


##### **Geri alma** 

- **git reset --hard HEAD** : 
- **git checkout HEAD <file>** :
- **git revert <yorum>** :
- **git reset --hard <yorum>** :
- **git reset <yorum>** : 
- **git reset --keep <yorum>** : 



## **Kaynaklar**:
### **Başlangıç**
- [Başlangıç 1](http://git-scm.com/book/en/Getting-Started-A-Short-History-of-Git)
- [Başlangıç 2](http://git-scm.com/book/en/Getting-Started-About-Version-Control)

### **Git tutorial** 
- [Git Basics 1](http://git-scm.com/book/en/Git-Basics-Recording-Changes-to-the-Repository)
- [Viewing The Commit History](http://git-scm.com/book/en/Git-Basics-Viewing-the-Commit-History)
- [Undoing Things](http://git-scm.com/book/en/Git-Basics-Undoing-Things)
- [Remotes](http://git-scm.com/book/en/Git-Basics-Working-with-Remotes)
- [Branches](http://git-scm.com/book/en/Git-Branching-What-a-Branch-Is)
- [Merging](http://git-scm.com/book/en/Git-Branching-Basic-Branching-and-Merging)
- [Branch Management](http://git-scm.com/book/en/Git-Branching-Branch-Management)
- [Workflows](http://git-scm.com/book/en/Git-Branching-Branching-Workflows)
- [Rebasing](http://git-scm.com/book/en/Git-Branching-Rebasing)

### **Ek kaynakalar**
- [Git Guide](http://rogerdudler.github.io/git-guide/)
- [Think like a git](http://think-like-a-git.net/)
- [Git Branching](http://pcottle.github.io/learnGitBranching/)
- [Visual Git](http://marklodato.github.io/visual-git-guide/index-en.html)
- [Git ready](http://gitready.com/)
- [Git Immersion](http://gitimmersion/)

### **Udemy kaynakları**
- [Türkçe kaynak](https://www.udemy.com/git-ve-github-kullanmayi-ogrenin/learn/v4)
- [İngilizce kaynak](https://www.udemy.com/git-started-with-github/)

### **Karışık türkçe kaynaklar**
- [Kaynak 1](http://selahattinunlu.com/git-ogrenmek-icin-kaynaklar)
- [Kaynak 2](https://forumlogs.com/t/git-ogrenmek-icin-kaynaklar-listesi/1043)
- [Kaynak 3](http://rogerdudler.github.io/git-guide/index.tr.html)
- [Kaynak 4](http://www.w3ii.com/tr/git/git_useful_resources.html)
- [Kaynak 4](https://aliozgur.gitbooks.io/git101/)
- [Kaynak 5](https://www.youtube.com/watch?v=rWG70T7fePg&list=PLPrHLaayVkhnNstGIzQcxxnj6VYvsHBHy)
- [Kaynak 6](http://git.gelistiriciyiz.biz/)
- [Kaynak 7](https://medium.com/@mustafazahidefe/git-notlar%C4%B1-2-git-i%CC%87nit-f54292fbf631)
- [Kaynak 8](https://medium.com/@noteCe)


