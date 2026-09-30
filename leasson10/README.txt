1. src-ის ნაცვლად უნდა იყოს href, და ჩავასწორე ეგ.
        <nav>
            <a src="#about">კურსის შესახებ</a> (შეცდომა ამაშია)
            <a href="#topics">თემები</a>
            <a href="#contact">კონტაქტი</a>
        </nav>

2. href-ის ნაცვლად უნდა იყოს src, და ჩავასწორე ესეც.
            <p>
                ეს არის Front-End პროგრამირების კურსი,
                სადაც HTML Markup-ს ვსწავლობთ.
            </p>

            <img href="html.jpg" alt="HTML logo"> (შეცდომა ამაშია)

3. p არის ჩაწერილი li-ს ნაცვლად.
            <ul>
                <p>HTML სტრუქტურა</p> (შეცდომა)
                <li>Semantic HTML</li>
                <li>Forms</li>
                <li>Tables</li>
            </ul>


3. th-ის ნაცვლად იყო td და ეგ ჩავასწორე.
                <thead>
                    <tr>
                        <td>სახელი</td> (შეცდომა ამაშია)
                        <th>კურსი</th>
                        <th>სტატუსი</th>
                    </tr>
                </thead>

4. for და id ერთმანეთს არ ემთხვევა.
            <form>

                <label for="name">სახელი</label>
                <input id="username" type="text">

                <br>