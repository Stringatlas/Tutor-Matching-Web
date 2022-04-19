<style>
    .listView {
        flex-direction: column;
        justify-content: start;
        align-items: flex-start;
    }

    .course {
        justify-content: start;
        margin-left: 1rem;
        padding: 1rem;
        border-radius: 10px;
        border-color: rgb(82, 1, 1);
        border-style: solid;
        border-width: 2px;
    }


    h2 {
        margin-top: -0.1rem;
        padding-left: 0.25em;
        padding-top: 0.1em;
        padding-bottom: 0.1em;
		background-color: coral;
    }

    h3{
        text-anchor: start;
        margin-top: -1rem;
        padding-left: 0.25em;
        padding-top: 0.1em;
        padding-bottom: 0.1em;
        background-color: rgb(175, 216, 203);
    }

    p {
        padding-left: 0.25em;
        padding-top: 0.1em;
        padding-bottom: 0.1em;
    }

    button {
        font-weight: bold;
        padding: 0.35em;
        color: rgb(200, 200, 200);
        background-color: rgb(23, 152, 34);

    }

    button:hover, button:active {
        
        color: white;
    }

    button:focus {
        background-color: rgb(23, 152, 34);
    }

    main {
        background-color: rgb(137, 192, 216);
		padding: 1em;
		margin: 1 auto;
    }

</style>

<h1>Courses </h1>

<main>
    <div class="listView">
        <div class="course">
            <h2>Course</h2>
            <h3>Grades 8-10</h3>
            <p>Description</p>
            <button>Details</button>
        </div>
    
        <div class="course">
            <h2>Geometry</h2>
            <h3>Grades 8-10</h3>
            <p>Shapes for school study othhtwiuoaeht iwuethoiwuaehgiuohagoi auwheuiowheaogihwa iuehtoiawue thiuoewaht ioeawhtioaweht oawieuth eaioheawiou thaweouit heawiohiwaeuth oiawethuiewathoiewau thioaewht uioewaht uioweaht iouaweth oiawouiewa thowehweauio</p>
            <button>Details</button>
        </div>
        
    </div>
</main>
