# WorldSkills Checklist

Some are applicable for practice only, some for competition only, some are for both.

## Editor

<ul>
    <li>Editor keyboard shortcuts</li>
    <li>Allowed editor extensions installed and working</li>
</ul>

## Environment

<ul>
    <li>
        AMPPS running (if applicable)
    </li>
    <li>
        Can I access my server? (if applicable) </br>
        For AMPPS:
        <code>http://localhost:80</code>
    </li>
    <li>
        Can I access my database? (phpmyadmin)<br>
        <code>http://localhost/phpmyadmin</code>
    </li>
    <li>
        Can I connect to the database? (Laravel)</br>
        in CMD: <code>php artisan tinker </code>
        </code> </br>
        <code>DB::connection()->getPdo();</code></br>
        On error, check credentials in <code>.env</code>
    </li>
    <li>
        Did I create a new database for the current project?
    </li>
    <li>
        Did I put the correct details into <code>.env</code>?
        <ul>
            <li>database type (mysql)</li>
            <li>database name</li>
            <li>username</li>
            <li>password</li>
            <li>host</li>
            <li>port</li>
        </ul>
    </li>
    <li>
        Is node working? </br>
        in CMD: <code>node --version</code>
    </li>
    <li>
        Is PHP working? </br>
        in CMD: <code>php --version</code>
    </li>
    <li>
        Is composer working? </br>
        in CMD: <code>composer --version</code>
    </li>
    <li>
        Is my selected framework running?
    </li>
    <li>
        Node port conflict (Vite only)
        in CMD: <code>npm run dev -- --port 4000</code>
    </li>
    <li>
        Node port conflict (backend only)
        in CMD: <code>set PORT=4000 && npm start</code>
    </li>
    <li>
        Laravel port conflict
        in CMD: <code>php artisan serve --port=8100</code>
    </li>
</ul>