🛠️ Kurulum Rehberi
Sunucunuzun dosyalarından plugins/Skript/scripts klasörüne giriş yapın.

Bu dizin içinde bakim.sk isminde yeni bir metin belgesi oluşturun.

Yukarıda paylaşılan kod bloğunu eksiksiz kopyalayarak bu dosyaya aktarın ve kaydedin.

Sunucu içerisinden veya konsoldan /sk reload bakim yazarak sistemi aktif hale getirin.

🗝️ Yetkilendirme
Bakım modunu yönetmek ve bakım sırasında sunucuya giriş yapabilmek için yetkilere skript.bakim iznini (permission) vermeniz gerekir.

Enes tarafından yapılmıştır.
"""

file_name = "bakim-readme.md"
with open(file_name, "w", encoding="utf-8") as file:
file.write(readme_bakim_content)

print(f"File generated successfully: {file_name}")
