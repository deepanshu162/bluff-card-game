<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bluff Game Rules</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }

        h1, h2 {
            color: #222;
        }

        section {
            margin-bottom: 30px;
        }

        ul, ol {
            margin-left: 20px;
        }

        .example {
            background: #f4f4f4;
            padding: 10px;
            border-left: 4px solid #555;
            margin: 10px 0;
        }
    </style>
</head>
<body>

    <h1>Bluff Game Rules</h1>

    <section>
        <h2>Objective</h2>
        <p>
            The objective of the game is to be the first player to get rid of all the cards in their hand.
        </p>
    </section>

    <section>
        <h2>Setup</h2>
        <ul>
            <li>Use a standard 52-card deck.</li>
            <li>Shuffle the deck thoroughly.</li>
            <li>Distribute all cards among the players. Some players may receive one more card than others if the cards cannot be divided equally.</li>
            <li>Choose a player to start the game.</li>
        </ul>
    </section>

    <section>
        <h2>Starting a Round</h2>
        <p>
            The starting player begins a round by placing one or more cards face down into the center pile and declaring a rank (Ace, King, Queen, Jack, or any numbered rank).
        </p>
        <p>
            The declared rank may be truthful or a bluff.
        </p>

        <div class="example">
            <strong>Example:</strong><br>
            A player places two cards face down and says, "Two Kings."<br>
            The cards may or may not actually be Kings.
        </div>

        <p>
            Once a rank has been declared for a round, that rank remains active for the entire round.
        </p>
    </section>

    <section>
        <h2>Player Actions</h2>

        <h3>1. Continue the Claim</h3>
        <p>
            The player places one or more cards face down onto the center pile and declares them to be of the currently active rank.
        </p>

        <p>
            The player must continue using the same declared rank as the current round.
        </p>

        <div class="example">
            <strong>Example:</strong><br>
            Player A declares "Two Kings."<br>
            Player B may place cards and must also declare them as Kings.<br>
            Whether the cards are actually Kings is up to Player B.
        </div>

        <h3>2. Call Bluff</h3>
        <p>
            The player may challenge the previous play by calling <strong>"Bluff!"</strong>
        </p>

        <p>
            When a bluff is called, the center pile is immediately revealed and resolved according to the Bluff Resolution rules.
        </p>

        <h3>3. Pass</h3>
        <p>
            The player may choose not to play any cards and pass their turn.
        </p>

        <h4>Passing Restriction</h4>
        <p>
            Once a player passes during a round, they may not play any cards into the current center pile for the remainder of that round.
        </p>

        <p>A player who has passed may still:</p>
        <ul>
            <li>Call Bluff on a later turn.</li>
            <li>Pass again when their turn comes around.</li>
        </ul>

        <p>
            The player may only play cards again after a new round begins.
        </p>
    </section>

    <section>
        <h2>Bluff Resolution</h2>

        <p>
            When a player calls <strong>"Bluff!"</strong>, all cards in the center pile are revealed.
        </p>

        <h3>If the Challenged Play Was a Bluff</h3>
        <ul>
            <li>The challenged player takes the entire center pile into their hand.</li>
            <li>The player who correctly called Bluff starts the next round.</li>
        </ul>

        <h3>If the Challenged Play Was Truthful</h3>
        <ul>
            <li>The player who called Bluff takes the entire center pile into their hand.</li>
            <li>The challenged player starts the next round.</li>
        </ul>
    </section>

    <section>
        <h2>Flushing the Pile</h2>

        <p>
            If every eligible player passes and no one chooses to play cards or call Bluff, the center pile is flushed.
        </p>

        <p><strong>When a pile is flushed:</strong></p>
        <ul>
            <li>All cards in the center pile are removed from play.</li>
            <li>No player receives the flushed cards.</li>
            <li>The player who made the last successful play before the flush starts the next round.</li>
        </ul>
    </section>

    <section>
        <h2>New Round Rule</h2>

        <p>A new round begins whenever:</p>

        <ul>
            <li>A bluff call has been resolved, or</li>
            <li>The center pile has been flushed.</li>
        </ul>

        <p>
            The player starting the new round may declare any rank they choose.
        </p>

        <p>
            Once a rank is declared, all players who choose to play cards during that round must continue declaring that same rank until the round ends.
        </p>
    </section>

    <section>
        <h2>Winning the Game</h2>

        <p>
            A player wins by getting rid of all cards in their hand.
        </p>

        <h3>Final Play Rule</h3>

        <p>
            A player cannot win until their final play survives any bluff challenge.
        </p>

        <ul>
            <li>If a player's final play is challenged and found to be a bluff, they must take the entire center pile and continue playing.</li>
            <li>If no player challenges the final play, or if the challenge proves the play was truthful, that player immediately wins the game.</li>
        </ul>
    </section>

    <section>
        <h2>Example Round</h2>

        <ol>
            <li>Player A places two cards face down and declares, "Two Kings."</li>
            <li>Player B places one card face down and declares, "One King."</li>
            <li>Player C passes.</li>
            <li>Player D places two cards face down and declares, "Two Kings."</li>
            <li>Player A calls "Bluff!" on Player D.</li>
            <li>The pile is revealed.</li>
            <li>If Player D lied, Player D takes the pile and Player A starts the next round.</li>
            <li>If Player D told the truth, Player A takes the pile and Player D starts the next round.</li>
        </ol>
    </section>

</body>
</html>
