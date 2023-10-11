
### Branch Oluşturma Kılavuzu

1.  **Branch İsimlendirmesi**:
    
    -   Branch isimleri belirli bir düzeni takip etmelidir. Önerilen düzen şu şekildedir:
    -      
        `` feature/AETG-****/branch-title `` 
        
    -   `AETG-****` kısmı, çalıştığınız taskın kodudur..
    -   `branch-title` kısmı, bu branch'in amacını özetler. Örnek olarak, "brand-listing" veya "fix-qr-transaction-issue" gibi açıklayıcı bir başlık olabilir.
    
		    Örnek:
            feature/AETG-7062/unpermitted-location-actions

### Commit Atma Kılavuzu

1.  **Commit Mesajı İsimlendirmesi**:
    
    -   Her commit mesajı da belirli bir düzeni takip etmelidir. Önerilen düzen şu şekildedir:
        
        `` <AETG-**** <feat/fix/chore>: <commit message> ``
        
    -   `AETG-****` kısmı, commit'in hangi özelliği, düzeltmeyi veya görevi ilgilendirdiğini temsil eder.
    -   `feat/fix/chore` kısmı, commit'in türünü belirtir. Örnek olarak, yeni bir özellik eklemek için "feat," bir hata düzeltmek için "fix," veya küçük ya da önemsiz string değiştirmeleri gibi işler için "chore" gibi.
    
		    Örnek:
            <AETG-7062 feat: unpermitted location flow has been changed
