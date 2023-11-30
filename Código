package com.example.exercicioquadrantecompose

import android.os.Bundle
import androidx.activity.ComponentActivity
import androidx.activity.compose.setContent
import androidx.compose.foundation.background
import androidx.compose.foundation.layout.Column
import androidx.compose.foundation.layout.Row
import androidx.compose.foundation.layout.fillMaxSize
import androidx.compose.foundation.layout.padding
import androidx.compose.material3.MaterialTheme
import androidx.compose.material3.Surface
import androidx.compose.material3.Text
import androidx.compose.runtime.Composable
import androidx.compose.ui.Alignment
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.text.font.FontWeight.Companion.Bold
import androidx.compose.ui.text.style.TextAlign.Companion.Justify
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.unit.dp
import androidx.compose.ui.unit.sp
import com.example.exercicioquadrantecompose.ui.theme.ExercicioQuadranteComposeTheme

class MainActivity : ComponentActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContent {
            ExercicioQuadranteComposeTheme {
                // A surface container using the 'background' color from the theme
                Surface(
                    modifier = Modifier.fillMaxSize(),
                    color = MaterialTheme.colorScheme.background
                ) {
                    Quadrant("Compose")
                }
            }
        }
    }
}

@Composable
fun Quadrant(name: String, modifier: Modifier = Modifier) {
    Column {
        Row {
            Column(
                Modifier
                    .weight(1f)
                    .background(Color(0xFFEADDFF))
                    .padding(16.dp)) {
                Text(
                    text = "Text composable",
                    fontWeight = Bold,
                    textAlign = Justify,
                    modifier = modifier
                        .padding(bottom = 16.dp)
                        .align(Alignment.CenterHorizontally)
                )
                Text(
                    text = "Displays text and follows the" +
                            " recommended Material Design guidelines.",
                    textAlign = Justify,
                    fontSize = 14.sp,
                    modifier = modifier
                         .padding(16.dp)
                )

            }
            Column(
                Modifier
                    .weight(1f)
                    .background(Color(0xFFD0BCFF))
                    .padding(16.dp)) {
                Text(
                    text = "Image composable",
                    fontWeight = Bold,
                    textAlign = Justify,
                    modifier = modifier
                        .padding(bottom = 16.dp)
                        .align(Alignment.CenterHorizontally)

                )
                Text(
                    text = "Creates a composable that lays out" +
                            " and draws a given Painter class object.",
                    textAlign = Justify,
                    fontSize = 14.sp,
                    modifier = modifier
                        .padding(16.dp)
                )

            }
        }

        Row {
            Column(
                Modifier
                    .weight(1f)
                    .background(Color(0xFFB69DF8))
                    .padding(16.dp)) {
                Text(
                    text = "Row composable",
                    textAlign = Justify,
                    fontWeight = Bold,
                    modifier = modifier
                        .padding(bottom = 16.dp)
                        .align(Alignment.CenterHorizontally)

                )
                Text(
                    text = "A layout composable that places" +
                            " its children in a horizontal sequence.",
                    textAlign = Justify,
                    fontSize = 14.sp,
                    modifier = modifier
                        .padding(16.dp)
                )

            }
            Column(
                Modifier
                    .weight(1f)
                    .background(Color(0xFFF6EDFF))
                    .padding(16.dp)) {
                Text(
                    text = "Column composable",
                    fontWeight = Bold,
                    textAlign = Justify,
                    modifier = modifier
                        .padding(bottom = 16.dp)
                        .align(Alignment.CenterHorizontally)

                )
                Text(
                    text = "A layout composable that places" +
                            " its children in a vertical sequence.",
                    textAlign = Justify,
                    fontSize = 14.sp,
                    modifier = modifier
                        .padding(16.dp)
                )

            }
        }
    }
}

@Preview(showBackground = true)
@Composable
fun QuadrantPreview() {
    ExercicioQuadranteComposeTheme {
        Quadrant("Compose")
    }
}
